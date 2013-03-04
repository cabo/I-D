# Internet-Drafts work in progress

This repository contains the source to various Internet-Drafts that are work in progress, in no particular state of completion, and invites others to make use of this work in progress.

They are in kramdown-rfc2629 form, which is a YAML header (mostly used for literature references) followed by one or more pieces of markdown text (kramdown flavor).

If you want to make use of these,

    gem install kramdown-rfc2629

get the latest version of [xml2rfc](http://xml.resource.org) and then use a command line such as

    kramdown-rfc2629 a-draft.mkd >a-draft.xml
    xml2rfc a-draft.xml

or simply use them as a quarry for markdown source, disregarding the YAML header.

As with all published Internet-Drafts, the license to these documents is as follows:

> This document is subject to BCP 78 and the IETF Trust's Legal Provisions Relating to IETF Documents (http://trustee.ietf.org/license-info) in effect on the date of publication of this document.  Please review these documents carefully, as they describe your rights and restrictions with respect to this document.  Code Components extracted from this document must include Simplified BSD License text as described in Section 4.e of the Trust Legal Provisions and are provided without warranty as described in the Simplified BSD License.

In addition, I grant all the rights under a Creative Commons 0 License:

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png"
         style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="http://github.com/cabo">
     <span property="dct:title">Carsten Bormann</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">Internet-Drafts</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="DE" about="http://github.com/cabo/I-D">
  Germany</span>.
</p>

So you have about as many copyright rights to this as I can legally grant in Germany.  Enjoy!
