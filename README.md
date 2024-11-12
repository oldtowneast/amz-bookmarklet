# Amazon "Add to List" Bookmarklet

This repository contains a simple bookmarklet to automate adding products to your Amazon list directly from the product page with just one click.

## Overview

The "Add to List" Bookmarklet allows you to add any product to your default Amazon list without going through the usual steps on the website. It's designed to streamline the process of managing your Amazon lists, making it more efficient and user-friendly.

## How It Works

The bookmarklet works by simulating a click on the "Add to List" button found on Amazon product pages. It uses JavaScript to target the button by its unique ID and triggers the button's functionality as if you clicked it manually.

## Installation

To use the bookmarklet, follow these steps:

1. Create a new bookmark in your browser.
2. Edit the bookmark's URL.
3. Copy and paste the following JavaScript code as the URL:

   ```javascript
   javascript:(function(){
     var button = document.getElementById('add-to-wishlist-button-submit');
     if (button) button.click();
   })();
   ```

4. Save the bookmark.

## Usage

Whenever you are on an Amazon product page and you want to add the product to your list, simply click the bookmarklet in your browser's bookmarks bar. The product will be added to your list automatically.

## Compatibility

This bookmarklet should work in any modern web browser, including Chrome, Firefox, Safari, and Edge. Ensure that your browser allows JavaScript to run from bookmarks for this bookmarklet to work correctly.

## Contributing

Contributions to improve the bookmarklet are welcome. Please feel free to fork the repository, make improvements, and submit a pull request.

## Disclaimer

This bookmarklet is provided "as is", without warranty of any kind. Use at your own risk. Also, be aware that Amazon's website updates could affect the functionality of this bookmarklet. Regular updates may be necessary to maintain its functionality.