---
description: >-
  This change log is specific to the manual & database specification only, not
  other site updates.
---

# Change Log

## 2.0.0 - 2018-10-28 - New System & Manual

This is the initial release of the second version of the Data Management tool and accompanying manual. The scope of the manual has expanded greatly from the original and is the point of reference for all users and moderators.

### New

* Characters, staff and banners are no longer separate submission forms, everything is now done through either submitting or editing the two anime and manga forms.
* Additional [sources](submission-form/general/typings/untitled-7.md) have been added to the website and all media types can now make use of the field. The new sources are:
  * **Doujinshi**
  * **Anime**
  * **Novel** 
    * _Any works adapted from full novels caught in the Novel to Light Novel change \(see_ [_fixed_](changelog.md#fixed)_\) will have to be manually corrected to the new Novel source._
* Two new opposite [relations](submission-form/relations.md), '**Contains**' and '**Compilation**', for linking [one-shots](before-you-begin/written-media-information/one-shots.md) into anthology collections and vice versa have been added to the website.
  * **Example**: [Shuuden ni wa Kaeshimasu](https://anilist.co/manga/85662/Shuuden-ni-wa-Kaeshimasu/)
* A [locked](submission-form/general/misc/locked.md) toggle to restrict ability to add and favourite entries has been added to the website
* [Characters](submission-form/characters/adding-characters.md) can now be imported from existing entries and then modified.
  * Staff import will come at a later date.
* You can now upload images directly from your device.
* A [tools](before-you-begin/sourcing/tools/) section has been included in the manual.
* A guide to [sourcing](before-you-begin/sourcing/) information has been included in the manual.
* A [romanisation](before-you-begin/romanisation.md) guide has been included in the manual.
* A [title formatting](before-you-begin/title-formatting.md) guide has been included in the manual.
* A [tags](tags/tag-management.md) guide has been included in the manual.
* The [Mod Tools](moderator/mod-tools.md) have been included in the manual.
* A list of [moderators](moderator/moderator-list.md) has been included in the manual.

### Fixed

* The **Novel** [format](submission-form/general/typings/untitled-6.md) is now correctly displayed as **Light Novel** throughout the website.
* **Character** relation will now set **Character** on the opposite relation.
* **Summary** relation will now set **Parent** on the opposite relation
* **Side Story** relation will now set **Parent** on the opposite relation.

### Changed

* The **Novel** [source](submission-form/general/typings/untitled-7.md) has been renamed to **Light Novel**
* **Parent** relation can no longer be set.
* The **Adaptation** [relation](submission-form/relations.md) has been changed so that it now has the opposite relation of **Source**, to make identifying the the source material easier.
  * **Example**: [Chihayafuru](https://anilist.co/manga/43245/Chihayafuru/)
* Light novel to manga adaptations that previously incorrectly used the **Alternative** relation will now use **Adaptation** and **Source**, being treated the same way as anime adaptations.
  * **Example**: [Mushoku Tensei](https://anilist.co/manga/85564/Mushoku-Tensei-Isekai-Ittara-Honki-Dasu/)
* Novels and Web Novels from any accepted [country of origin](submission-form/general/typings/untitled-8.md) are not eligible to be in the database and any existing entries that have been added over time have been or will be deleted. The only allowed novel type is [Light Novel](before-you-begin/written-media-information/light-novels.md).
  * _Effect should be minimal as barely any users track Chinese or Korean web novels on this site, as much better alternatives are available. Professionally published manhua and manhwa are still allowed._
* The incorrect statement on the previous manual that extra chapters \(such as prologues, epilogues and .5's\) are not included in the total chapter count has been removed.
  * Effect should be minimal as they were still being included.
* Recommended minimum [image dimensions](before-you-begin/image-dimensions-and-template.md) for creating or cropping images have been changed
* The doujin format has now been replaced by a [licensed](submission-form/general/misc/licensed.md) toggle to specify whether the work is [doujinshi](before-you-begin/written-media-information/doujinshi.md).



