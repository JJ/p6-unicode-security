# Some notes on Unicode security

* [Unicode security guide](http://websec.github.io/unicode-security-guide/), things that can (and will) go wrong.

* [Internationalized Domain Names, IDN in Google Chrome](https://www.chromium.org/developers/design-documents/idn-in-google-chrome), how to deal with them to avoid spoofing or phishing; a [primer on that by James Seng](http://www.circleid.com/posts/idn_and_homographs_spoofing/). IDN was proposed [in this RFC](http://www.faqs.org/rfcs/rfc3490.html). Description of [IDN homograph/homoglyph attack](https://en.wikipedia.org/wiki/IDN_homograph_attack). 

* Homoglyphs are letters that look the same. [An homoglyph attack generator](https://www.irongeek.com/homoglyph-attack-generator.php). 

* [Ways Unicode can be used as attack vector](http://www.idnnews.com/?p=7109), by Chris Weber, with a [corresponding presentation](https://www.owasp.org/images/5/5a/Unicode_Transformations_Finding_Elusive_Vulnerabilities-Chris_Weber.pdf). Another synthesis in [lookout.net](https://www.lookout.net/2008/11/unicode-attacks-and-test-cases-visual.html). 

* [Punycode, a way of transforming unicode names to a standard](https://github.com/FROGGS/p6-IDNA-Punycode/blob/master/lib/IDNA/Punycode.pm), in a Perl 6 module and [general description](https://en.wikipedia.org/wiki/Punycode). 

* [A table of characters used in more than one script](http://ftp.unicode.org/Public/UNIDATA/ScriptExtensions.txt), or ScriptExtensions-11.0.0.txt; also [recommended confusable mapping for IDN](http://www.unicode.org/Public/security/revision-03/confusablesSummary.txt), both by the Unicode consortium. A utility that [finds confusables](http://unicode.org/cldr/utility/confusables.jsp), and the [TR39 for Unicode security mechanisms](http://www.unicode.org/reports/tr39/). 

