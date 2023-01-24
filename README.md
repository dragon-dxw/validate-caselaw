Local validation for case law

For The National Archives' [Find Case Law](https://github.com/nationalarchives/ds-find-caselaw-docs) project


* `script/setup` will download the
  [schemas](https://github.com/nationalarchives/ds-caselaw-marklogic/tree/main/src/main/ml-schemas)
  from Github
* `script/fetch` takes a full caselaw url (e.g. https://caselaw.nationalarchives.gov.uk/ukut/lc/2022/342)
  and downloads it to `downloaded.xml`
* `script/validate` validates an XML file against the schemas -- takes a filename, defaults to `downloaded.xml`

(Don't forget to copy these to ds-caselaw-marklogic/src/main/ml-schemas if you change them!)
