How to use carousels in portfolio:

Due to interaccions within page of multiple carussels, each carousel needs its own index. When adding a new entry in portofolio, add n empty entries and use that number for carousels number. Ex: say this is the 5th entry, add:
carousels:
  - images:
  - images:
  - images:
  - images:
  - images:
    - image: "here goes image path 1"
    - image: "here goes image path 2"

include carousel.html height="80" unit="%" duration="200" number="10"
---------------------


[Based on Agency Jekyll Theme](https://github.com/raviriley/agency-jekyll-theme)


The Jekyll structure of this theme includes:

- `_portfolio` files - what generate the portfolio grid. YAML front matter handles all the details
- the `page` layout allows custom pages, as seen in the legal and 404 pages
- `sitetext.yml` enables complete customization of all site text
- `navigation.yml` enables fully customizable navigation
- `style.yml` enables fully customizable colors, background images, and other style-related things


## Installation

There are three ways to install this theme:

1. As a gem-based theme
2. Use the [starter template][template] (best for GitHub Pages)
3. As a remote theme

#### 1. Gem-based Theme Installation

Replace the contents of your `_config.yml` file with the sample [\_config.yml](https://raw.githubusercontent.com/raviriley/agency-jekyll-theme/master/_config.yml).

Install the gem with:

```sh
$ bundle add jekyll-agency
```

Or manually.

1. Add this line to your Jekyll site's `Gemfile`:
   ```ruby
   gem "jekyll-agency"
   ```
2. Then execute:
   ```sh
   $ bundle install
   ```

#### 2. Using the [Starter Template][template]

This is the fastest and easiest way to get up and running on GitHub Pages.

Simply generate your own repository by clicking the button below. Then replace the sample content with your own and configure for your needs.

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)][generate]

</div>
    
#### 3. Remote Theme Installation

Replace your `_config.yml` file with the starter [\_config.yml](https://raw.githubusercontent.com/raviriley/agency-jekyll-theme-starter/master/_config.yml).

Replace your `Gemfile` with the starter [Gemfile](https://raw.githubusercontent.com/raviriley/agency-jekyll-theme-starter/master/Gemfile).

Then install gems.

```sh
$ bundle install
```
