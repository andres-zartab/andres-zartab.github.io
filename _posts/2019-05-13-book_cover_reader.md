---
layout: post
title: Book Cover Reader
git: https://github.com/andres-zartab/book_cover_reader
---

This is a tool for the book's inventory management of Tu Libro a Ciegas using Google Cloud.
Tired of manually updating your available books? Try this instead!
    - Take a picture of the desired book covers
    - Upload them to Google Storage
    - Google Vision will capture the text within the pictures
    - A request to Google Books API is done using the captured query
    - Most relevant info (authors, isbn code, etc) is logged into BigQuery

Feel free to use it, you'll only need a google cloud account!