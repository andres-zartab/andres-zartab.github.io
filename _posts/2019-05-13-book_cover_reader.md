---
layout: post
title: Book Cover Reader - Python
git: https://github.com/andres-zartab/book_cover_reader
---

This tool was created for the book's inventory management of Tu Libro a Ciegas using Google Cloud.

Take picture of book cover->Upload to Google Storage->Google Vision will capture the text->Google Books API request using the captured query->Book info (authors, isbn code, etc) and errors are logged into BigQuery

Feel free to use it, you only need a google cloud account.