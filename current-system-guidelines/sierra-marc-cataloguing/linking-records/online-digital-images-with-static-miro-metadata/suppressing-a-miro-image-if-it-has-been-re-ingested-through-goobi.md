# Suppressing a Miro image if it has been re-ingested through Goobi

Occasionally, Digital Production need to reingest a digital image if the Miro image is incorrect (i.e. needs to be flipped, rotated) or they have a higher quality image available.

If a Miro image exists, continue to put the image reference number in MARC field `089` (so the reference can be searched for in Sierra, using o Reference number as an index). This will be important if a Reader has a reference number from Wikimedia Commons and can't find it in our catalogue.

{% hint style="warning" %}
Merged Miro images appear in a catalogue record like this:

![](<../../../../.gitbook/assets/image (12).png>)
{% endhint %}

Adding a `089` will merge any orphaned Miro image (if exists) with the catalogue record for the physical item.&#x20;

However, if the image is reingested because the Miro image is incorrect/needs editing then the old Miro image needs to be suppressed.

{% hint style="success" %}
In the bibliographic record for the item that has a newly reingested image, add the following to suppress the Miro image:\
\
`759 digmiro`
{% endhint %}

{% hint style="info" %}
Digital images (or fully digitised works) from Goobi appear on the catalogue like this:

![](<../../../../.gitbook/assets/image (13).png>)
{% endhint %}
