# News

In this repository, we store as text file the news to be presented to our users via the 'update banner' feature.

The files must be inside a folder which must be named LANGUAGE_REGION, where LANGUAGE and REGION are 2-letter codes. This naming convention is a subset of the [IETF language tag standard](https://en.wikipedia.org/wiki/IETF_language_tag) and may be expanded to support other tag formats as needed.

The files must contain a JSON object following the structure: 

```
{
  "title": "STRING"
  "body": "STRING"
}
```
