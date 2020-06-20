# GalComm Blocklist
Formatted HOSTS blocklist for 15K domains researched by Awake Security; combats malicious Chromium extensions.

File here: https://raw.githubusercontent.com/jerrimath/GalComm_Blocklist/master/Galcomm-Hosts-Formatted.txt

To use more stable versions, please use the Releases tab to find a desired major modification/addition to the blocklist.

> :warning: **DO NOT VISIT ANY OF THE DOMAINS IN THIS BLOCKLIST UNLESS YOU KNOW WHAT YOU'RE DOING.** :warning:

All credit goes to the Awake Security team. I do not intend to profit from this and have only done this out of goodwill for the community.

To read more, please see this link here: <https://awakesecurity.com/blog/the-internets-new-arms-dealers-malicious-domain-registrars/> <br/>
Their pdf report is also uploaded in this repo.

Original list can be found in tabbed format here: <https://awakesecurity.com/wp-content/uploads/2020/06/GalComm-Registered-Domains-List-Appendix-A.txt.>
It is also uploaded in this repo.

Modifications performed to the TSV were:

- Stripped Category names off
- Added 0.0.0.0 to comply with HOSTS format

## Important Update 2020 June 20

It was brought to my attention that I was missing a few URLs, namely from Appendices C thru D. I have therefore added the missing URLs from the PDF. Changes/improvements that have been implemented include:

- Readding categories and appendicies via comments in between URL blocks.
- Adding appendix C/D.
- Creation of two sublists for URLs in only appendix A and only appendicies C/D respectively. The main blocklist is all URLs combined from appendicies A, C, and D.
- Versioning via the version tab. This is thus version **v1.1**.

## How to use this blocklist

You can feel free to add this to your blocking software like Pi-Hole or otherwise. You should only do so if you know what you are doing, and if you can undo potential damage involved. I am not responsible for any damage that you cause by misimplemnting this blocklist. I am also not responsible for any damage that you cause by visiting any of the domains in the blocklist.

---

 **Future Updates**

 I do not anticipate updating this list in the future, unless a substantial update is released by the Awake Security team. Treat this list as-is. Hopefully it will be incorporated into bigger blocklists in the future. Please add issues on the original Reddit post, under the issues tab in the Github web GUI, or via a pull request.

---

## Licenses

License for my modifications (not the list of domains):

### **The MIT License (MIT)**

Copyright © 2020 Jerry Xu

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the “Software”), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
