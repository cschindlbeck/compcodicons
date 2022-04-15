# What is Compcodicons?

Compcodicons is a specialist icon font set for competitive coding / programming. It contains icons for websites and organistions related to competitive coding and programming that are often missing from mainstream repositories. 

Basically, it is an amateurish rip-off from [Academicons](https://jpswalsh.github.io/academicons/) for Competitive Coding.

An example can be seen on the sidebar of my [website](https://cschindlbeck.github.io/).

# Usage 

## HTML

Install Compcodicons on your site by placing the fonts and css folders on your server and link to the compcodicons.css stylesheet by adding the following to the page header:

```html
<link rel="stylesheet" href="/path/to/folder/css/compcodicons.css"/>
```

Call the icons via

```html
<i class="cci cci-hackerrank"></i>
```

## Jekyll


1. Clone compcodicons

    ```sh
    git clone https://github.com/cschindlbeck/compcodicons
    ```

2. Copy font files (compcodicons.woff,compcodicons.tff) to assets/fonts

3. Copy compcodicons.css file to assets/css

4. Include css file in \_includes/head.html:

    ```sh
      <link rel="stylesheet" href="/assets/css/compcodicons.css">
    ```
5. Add to \_config.yaml:

    ```yaml
    author:
      links:
        - label: "Hackerrank"
          icon: "cci cci-hackerrank"
          url: "https://www.hackerrank.com/schindlbeck"
    ```

# License

TODO

# Author

- GitHub: [https://github.com/cschindlbeck](https://github.com/cschindlbeck)



