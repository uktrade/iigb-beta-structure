# IIGB website structure

<!-- toc -->

- [The purpose](#the-purpose)
- [Getting Started with development](#getting-started-with-development)
  * [Get the source](#get-the-source)
  * [Project/File Structure](#projectfile-structure)
- [Deployment & Release](#deployment--release)

<!-- tocstop -->

## The purpose
This repository contains the webiste structure for the IIGB website in a format that can be pulled in by the website as a node module and used bu metal-smith to build out the static pages that make up the site.

## Getting Started with development

### Get the source
Run the following from the command line to download the repository and change into the directory:

```bash
git clone git@github.com:uktrade/iigb-beta-structure.git

cd iigb-beta-structure
```

### Project/File Structure

Below snippet outlines project structure. This snippet only lists files of importance.

```
- redirects/
  - ip_redirects.json #Defines the mapping of IP geo locations to the languages used in the website.
- structure/          #Contains files that define the page heirarchy and content sources for each of the languages and locations supported by the website.     
- package.json        
- README.md           

```

## Deployment & Release

Branch `develop` is continuously deployed to [staging environment](https://staging.invest.great.gov.uk/) for QA purposes, using the current version of the `develop` branch for the iigb-beta-website repository.
