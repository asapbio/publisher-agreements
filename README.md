# Compiling publication agreements used by scholarly journals

This repository aims to compile a list of agreements used by scholarly publishers.
It attempts to provide a resource to answer the [following tweet](https://twitter.com/dhimmel/status/987019183723569152):

> Does anyone know of a compilation of copyright transfer / license to publish agreements used by scholarly journals? #asapbio

## Files

[`01.romeo.ipynb`](01.romeo.ipynb) downloads information from SHERPA/RoMEO's API and extract copyright links.
Links are saved in `data/romeo-publisher-links.tsv`.

## License

All original work in this repository is dedicated to the public domain under the CC0 license.
See [LICENSE.md](LICENSE.md).

[SHERPA/RoMEO](http://www.sherpa.ac.uk/romeo/index.php) releases its data downloads under a [CC BY-NC-SA 2.5](https://creativecommons.org/licenses/by-nc-sa/2.5/) License according to the following statement in [`romeo-publishers.xml`](data/romeo-publishers.xml):

> SHERPA/RoMEO data is available for re-use under a Creative Commons Attribution-Non-Commercial-Share Alike 2.5 licence.
For more details, please see the 'conditions for re-use' at http://www.sherpa.ac.uk/romeoreuse.html, and linked-to from the SHERPA/RoMEO home page.

Therefore, datasets derived from `romeo-publishers.xml` in this repository are also released under a CC BY-NC-SA 2.5 License.
This includes [`romeo-publisher-links.tsv`](data/romeo-publisher-links.tsv).