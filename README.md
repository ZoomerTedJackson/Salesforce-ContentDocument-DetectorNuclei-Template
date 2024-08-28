
<div align="center">
<h3 align="center">Salesforce ContentDocument Detector Nuclei Template</h3>
  <p align="center">
    A Nuclei Template that checks if a website is running Salesforce Lightning and then attempts to see if guest users are authorized to retrieve files
    <br />
  </p>
</div>
<h2>About</h2>
I wrote this up to automatically check for websites that have Salesforce Lightning and let me download files so I can check for permissions issues in Bug Bounties that allow me to access files i shouldn't
 <br /> <br />

<h2>Usage</h2>
This should work fine with Nuclei, and a medium-severity item should be returned if successful. You may disagree with having a medium severity for something informational like this, but that's a personal choice because I always want to check out websites that hit on this check.

```
python ./main.py /path/to/file.json
```
