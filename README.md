
# Little Prince 👋
Little Prince is an application that stores your favorite adult movies in a database and syncs them with your storage.

![Movie View](files/image_jav_landing_page.png)
_Little Prince home_

## Requirements
Little Prince is a desktop application that supports both Windows and MacOS (coming soon). You can check the [latest version here](https://github.com/little-prince-app/little-prince-app/releases).

## Features
* Sync data from meta.json files in Storage.
* Import movie data to the database from the JAV code.
* Show the movie list and details.
* Sort movie data by Rating, Release date, and Number of actresses.
* Sort actresses by name, rating, cup, and height.
* Search movie from the code, movie title, genre, and actress name.
* Supports user ratings for movie and actress favorites.
* Download basic movie information such as name, cast, and genre.
* Download actress images.
* Download movie screenshots.
* Group movie data by genre.
* Group movie data by maker.
* Group movie data by code prefix and details about file size.
* And more...

## Little Prince Overview

Little Prince App helps you organize your movie database, giving you easy access to search and filter by title, genre, actress and more. You can also sort by title, movie code, cast, release date and your own rating.

![Movie View](files/image_jav_movie_gridview.png)
_Little Prince movie viewer_

When you click on a movie in the movie list, the app will show you the movie details including movie title, cover, genre, cast, screenshots and all info related.

![Movie View](files/image_jav_movie_detail_view.png)
_Little Prince movie detail page_

You can customize the data as you want, or let the app download metadata from the internet.

![Movie View](files/image_jav_movie_detail_view_form.png)
_Little Prince movie detail_

You can also choose to view the movie list from the List view mode.

![Movie View](files/image_jav_movie_list_view.png)
_Little Prince movie_

Detailed view To view a large amount of detailed information.

![Movie View](files/image_jav_movie_list_detail_view.png)
_Little Prince movie_

## Actresses

You can add your favorite actresses, specify their name, cup, picture, and choose how to sort and filter the data.

![Movie View](files/image_jav_actress_view.png)
_Little Prince actress viewer_

When you click on the actress's picture, it will show you the details page and related movies. You can customize the information as you want or let the app download the data from the internet as well.

![Movie View](files/image_jav_actress_detail_view.png)
_Little Prince actress detail_

## Folder Structures

Information about the structure of the file storage. You need to specify the path of the folder first. You can do this in the Database menu. For example, N:\LITTLE_PRINCE

It will contain the following structure folders.
Example for GVG-343

```
LITTLE_PRINCE
    │
    └─JAV
        ├─movies
        │    └─GVG
        │        │  
        │        ├─GVG-343
        │        │    │  GVG-343.jpg
        │             │  GVG-343.mp4
        │             │  feature.jpg
        │             │  meta.json
        │             ├─ screenshots 
        │                       └─  ...
        │
        │
        └─actresses
            ├─EIMI_FUKADA
            │   │  main.jpg
            │   
            ├─SUZU_HONJO
            │   │  main.jpg
```

## Metadata of Movie

The data for movies will be stored in a file called meta.json, which will be stored in a separate folder for each movie code.

Example of data inside the meta.json file.
N:\LITTLE_PRINCE\JAV\movies\GVG\GVG-343\meta.json

```
{
    "code": "GVG-343",
    "content_id": "gvg00343",
    "release_date": "2016-08-03",
    "duration_minute": null,
    "director": "Sean Saito",
    "maker": "Glory Quest",
    "series": null,
    "genres": [
        "BIG TITS",
        "OUTDOOR",
        "THREESOME / FOURSOME"
    ],
    "rating": 3,
    "movie_title": "Big-Titted Masochistic Women Dumped Naked In Woods",
    "movie_title_custom": "Bondage 4 Big-Titted",
    "story": null,
    "note": null,
    "count_actress": 4,
    "actresses": [
        "MIKAN KURURUGI",
        "MINAMI AYASE",
        "MION HAZUKI",
        "SERINA FUKAMI"
    ],
    "scenes": [],
    "has_subtitle_file": false,
    "has_climax_gif": false,
    "has_preview": false
}
```

## Metadata of Actress

The data for actress will be stored in a file called meta.json, which will be stored in a separate folder for each actress name.

Example of data EIMI_FUKKADA inside the meta.json file.
N:\LITTLE_PRINCE\JAV\actresses\EIMI_FUKADA\meta.json

```
{
    "name": "EIMI FUKADA",
    "name_other": null,
    "birth_day": "1998-03-18T00:00:00.000",
    "debut_date": "2018-11-03T00:00:00.000",
    "cup": "H",
    "height": 159,
    "rating": 3
}
```

## Tools

The app has tools to help you import and download data quickly.
* Import movies with code.
* Download movie cover.
* Download movie metadata.
* Import actress with name.
* Download actress image.
* Download actress metadata.

![jav tool](files/image_jav_tool.png)
_Little Prince jav tools_

Example of adding multiple movie codes at once.

![Importing movie](files/image_jav_importing_movie_page.png)
_Little Prince adding movie_

Example of downloading multiple movie cover.

![Downlaoding cover](files/image_jav_download_movie_cover_page.png)
_Little Prince downloading movie cover_


Example of downloading meatadata of movie.

![alt text](files/image_jav_download_movie_metadata_page.png)

## Support us

[Buy Me a Coffee](https://buymeacoffee.com/little.prince)














