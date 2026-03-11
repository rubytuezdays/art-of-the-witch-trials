---
title: Data Management Plan
layout: page-narrow
permalink: /dmp.html
---
**Data Management Plan**

**Project Description**

This project is a digital collection made up of 14th \- 18th Century European artistic depictions of witches, witchcraft, and its punishments. To create this project, prints, paintings, lithographs, and engravings were collected from 8 different museums and aggregators from across the globe. This collection is hosted as a website on GitHub, a platform that allows users to host and share their code. This collection specifically uses CollectionBuilder Sheets, a template that formats a Google Sheets derived CSV of metadata into a website. This website, as a result, allows users to view, search, and group items by various features. 

**Anticipated Data**

This data was collected from multiple libraries, galleries, and online aggregators, which were used to find the object and relevant metadata. Most of the objects within this collection were individual pieces of artwork, with only a few items being art from within larger bodies of works like manuscripts or news reports. 

| Item Description | File Type | Size (in MB) | \# of Items | License(s) | Sources |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Images depicting witches, witchcraft, and punishments** | **jpg** | **7.3**  | **17** | **Public Domain, Creative Commons** | **Bodleian Library; University of Oxford, Internet Archive, Karlsruhe State Art Gallery, Rijks Museum, The Cleveland Museum of Art, The Metropolitan Museum of Art, The National Gallery, Wellcome Collection, Zentralbibliothek Zürich** |
|  |  |  |  |  |  |

Through the use of CollectionBuilder, hosted by Github, users can manipulate and access the data of this collection. Google Sheets needs to be available to adjust the code of this collection, no other tools are needed outside of what is built in to CollectionBuilder

**Documentation and Metadata**

The data dictionary is included at the end of this plan, and the data for every object in this collection is published as a tab labeled “data,” available for all viewers to see and use to understand the subject categories and details of the objects. 

**Storage and Backup**

The data for this project is primarily stored on GitHub, with one copy of each existing on a personal device that has them stored with Google Drive, and automatically backed up into the cloud. 

**Data Sharing**

The data making up this collection will be available through a CollectionBuilder website which details the creator, date, and location for the items, aiding in the ability to reuse these items. The original repository that each item is stored within is also linked, allowing users to easily find, download, and use the item. 

**Period of Data Retention**

This collection will be maintained for the duration of this course, as well as through the following spring term of 2026, with consistent checks and debugging attempts if necessary. Following the conclusion of this academic year in June 2026, the site will be irregularly maintained, but remain up for viewing as long as functioning. 

**Licensing and Ethical Issues**

All of the items in this collection have no known copyright and are public domain, or are under Creative Commons licensing, allowing them to be used within this collection as there is no commercial aspect of this collection. 

**Appendix: Data Dictionary**

| field | definition | example |
| :---- | :---- | :---- |
| objectid | Unique identifier for each object | coll001 |
| filename | Name of file, including file type extension.  | the\_four\_witches\_1497.jpg |
| title | Title of painting as stated by original repository.  | The Four Witches (Four Naked Women) |
| creator | The name of the creator of the object.  | Albrecht Dürer  |
| date  | When the object was created. | 1497 |
| description | A detailed description of the object, as illustrated. | Four naked witches stand together under an orb, skulls and bones at their feet and a devilish figure peeking from the corner. |
| medium | The artistic medium the object was created in. | engraving |
| subject | The main feature of the object or the scene the object illustrates. | witch(es) |
| location | The object’s country of origin. | Germany |
| source | A link to the original repository where the item is found. | [https://www.clevelandart.org/art/1964.22?utm\_source=art\_detail\_share](https://www.clevelandart.org/art/1964.22?utm_source=art_detail_share) |
| identifier | Specific identifier used for the object by the repository housing the object. | 1964.22 |
| type | Further specification of the object, as an image, stillimage, movingimage, text, etc.  | image;stillimage |
| format | The object’s file type. | image/jpg |
| rights | The rights of the object as stated by the original repository.  | You can copy, modify, and distribute this work, all without asking permission. Learn more about CMA's Open Access Initiative. |
| rights statement | Link to the rights statement defining how the object can be used. | [https://rightsstatements.org/page/NoC-US/1.0/?language=en](https://rightsstatements.org/page/NoC-US/1.0/?language=en) |

