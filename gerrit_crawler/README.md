## Introduction

This crawler retrieves gerrit information and generates statistics for various projects. The original code was designed for GitHub repositories, so I customized it to convert gerrit data formats to match GitHub's structure. Using Python, it extracts commits (ID, author, date, related reviews, files affected) and reviews (ID, date submitted, reviewers, files changed). The data populates CSV files following our template (see paper for details).

## To Use

Specify the gerrit URL and project name. It's that simple! The crawler does the rest.

## Background
We created this crawler for a 2023 paper by the **[ISE Lab](http://ise.ce.sharif.ir/)** at Sharif University of Technology. It tests our methodology on real-world gerrit projects.

**Note**: In Iran, connect through a VPN before running the crawler. Gerrit access may be blocked otherwise.

October 17, 2023