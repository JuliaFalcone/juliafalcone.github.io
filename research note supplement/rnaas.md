# A Supplement for My Research Note:

In my research note, I describe how to use Google sheets to display thousands of spectra from SDSS easily in Google Sheets. However, not everyone may be as familiar with how to data from SDSS and use Google Sheets, so this post is an attempt to be as explicit about these steps so that anyone, regardless of their familiarity with these processes, can still benefit from them.

## Part 1: Obtaining Data From SDSS

As I describe in my note, one can query the data from the [SDSS SkyServer Search Form](http://skyserver.sdss.org/dr16/en/tools/search/form/searchform.aspx). Below is a picture of an example query, in the event that I am looking for all galaxies with (RA, dec) = (30,180) within a radius of 180 arcminutes and which are associated with a spectrum.  I have circled in red all the options which must be manually changed to get the desired query.

![hi](skyserver_edited.png)

Once all the appropriate boxes have been selected, hit "Generate Query" at the bottom of the page. Once the box has text in it, Skyserver is ready to be queried. Once you ensure that the output format is a CSV (image below), click "Submit Query to Skyserver" for the data to be downloaded to your computer.

![](skyserver_submitted_edited.png)


```python

```
