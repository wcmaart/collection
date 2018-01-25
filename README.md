[![DOI](https://zenodo.org/badge/82729276.svg)](https://zenodo.org/badge/latestdoi/82729276)

# Williams College Museum of Art (WCMA) Collection

The Williams College Museum of Art is an innovative campus museum with a growing art collection at its heart. The [WCMA collection](https://wcma.williams.edu/collection/) includes works of art in all media ranging from ancient Egyptian, Assyrian, and Greco-Roman objects, Indian painting, African sculpture, photography, art of the U.S., and international modern and contemporary art. WCMA’s collection also features the world’s largest repository of work by the artist-brothers Maurice (1858-1924) and Charles Prendergast (1863-1948). WCMA has collected works of art uniquely suited for teaching; generations of Williams students have gone on to become museum directors, curators, gallerists, and educators.

WCMA is pioneering new ways to interact with the collection. In [Object Lab](https://wcma.williams.edu/object-lab-collaborate/), faculty select works of art that become lenses for classes to explore neuroscience, or botany, or religion. Collection objects are loaned to students through [WALLS](https://wcma.williams.edu/walls/), encouraging long-term personal connections. The [Rose Object Classroom](https://wcma.williams.edu/rose-object-classroom/) allows artworks to be used in a classroom space. WCMA’s Reading Room encourages [timely public conversation](https://wcma.williams.edu/getting-a-read-on-basquiat-and-black-lives-matter-2/) around individual works of art. The [release of this dataset](https://medium.com/@caw_/new-dimensions-for-collections-at-wcma-72d4c627fef8#.d7ja01dx7) is another way to open the collection for interaction, inspiration, research and innovative use.

This research dataset contains contains about 15,600 records, representing all currently accessioned works of art in WCMA’s collection. It includes basic metadata for each artwork, including accession number, title, date, classification, medium, and dimensions.

The dataset is generated in a way that other museums can copy. Data is exported from the front-end, client-side desktop application of TMS (a popular collections management system) with a [ListView profile](https://github.com/wcmaart/tms-listview-import). You don't need database access or deep technical expertise to export a similar dataset. 

At this time, the dataset is available in CSV format, encoded in UTF-8. While UTF-8 is the standard for multilingual character encodings, it is not correctly interpreted by Excel on a Mac. Users of Excel on a Mac can convert the UTF-8 to UTF-16 so the file can be imported correctly.

This dataset is placed in the public domain using a [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).


## **Usage guidelines**

### **Images**

Not all objects in the collection have images.

When an object does have an image, the filename for the image is listed in the dataset.

A thumbnail service ([view source](https://github.com/wcmaart/getThumb)) is available for individual objects based on object IDs: 

https://get-thumb.herokuapp.com/getThumb.php?objectid=xxx 

You may also download a [complete set of thumbnail images](https://rs.williams.edu/pages/view.php?ref=92421&k=0e4c94d372) that correspond with the filenames in the dataset. (2 Gb zip)

Images are not covered under the same license as the dataset; image thumnails are intended for educational and creative use.

### **Research in progress**

This data is provided “as is” for research purposes and you use this data at your own risk. Much of the information included in this dataset is not complete and has not been curatorially approved. WCMA offers the datasets as-is and makes no representations or warranties of any kind.

We plan to update the dataset with new and revised information on a regular basis. You are advised to regularly update your copy of the datasets to ensure you are using the best available information.

### **Pull requests**

Because the dataset is generated from our internal database, we do *not* accept pull requests. If you have identified errors or have extra information to share, please email us and we will forward to the appropriate department for review.

### **Give attribution to WCMA**

Our dataset is being offered under [CC0 1.0 Universal license](https://creativecommons.org/publicdomain/zero/1.0/).

Even though it’s not required, WCMA requests that you actively acknowledge and give attribution to WCMA wherever possible. If you use one or both of the datasets for a publication, please cite it using the digital object identifier [![DOI](https://zenodo.org/badge/82729276.svg)](https://zenodo.org/badge/latestdoi/82729276). Attribution supports efforts to release other data. It also reduces the amount of “orphaned data,” helping retain links to authoritative sources. And it’s just nice.

### **Do not misrepresent the dataset**

Do not mislead others or misrepresent the dataset or its source. You must not use WCMA’s trademarks or otherwise claim or imply that WCMA endorses you or your use of the dataset.

Whenever you transform, translate or otherwise modify the dataset, you must make it clear that the resulting information has been modified. If you enrich or otherwise modify the dataset, consider publishing the derived dataset without reuse restrictions.

The writers of these guidelines thank [MoMA](https://github.com/MuseumofModernArt/collection), [Carnegie Museum of Art](https://github.com/cmoa/collection), [Tate](https://github.com/tategallery/collection), and [Cooper-Hewitt](https://github.com/cooperhewitt/collection).

## Related Projects

- [*Accession Number*](https://wcma.williams.edu/exhibit/accession-number/), an exhibition at WCMA that displays works collected between 1960 and 1962, displayed in order by accession number.

- [Gallery Displays](https://github.com/williamscollege/gallery_displays), an in-gallery interactive installation that encourages visitors to arrange works of art from the exhibition *Accession Number*.

- [WCMADATA](https://docs.google.com/spreadsheets/d/1AESANVb_xlyGa7WTgtaGviwtt1L6SC0yACH10MRtR3c/edit#gid=861257992) a data viz sketch in Google Sheets.

- [*Pink Art*](https://wcma.williams.edu/pink-art/) an exhibition at WCMA that explores the usefullness of algorithms as curatorial tools. Students from the Computer Science department were given collection data and images; they created algorithms to sort the collection by color.

- [*The 60's and 70's at the WCMA*](http://artsatwilliams.com) a data-driven exploration of the WCMA collection during turbulent times. Submitted by a group of students at UCLA as a [final project](http://miriamposner.com/classes/dh101f17/assignments/final-project/) for a Digital Humanities 101 class, taught by Prof. Miriam Posner.

  ​

  Building a project with WCMA collection data? [Let us know.](mailto:cw11@williams.edu)

