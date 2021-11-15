# :pizza: PizzaApp
<div id="badges" align="center">
    <img src="https://img.shields.io/github/last-commit/aiden2480/12A1-PizzaApp?color=8e0000&logoColor=23272A&style=flat-square" alt="GitHub last commit" />
    <img src="https://img.shields.io/github/commit-activity/m/aiden2480/12A1-PizzaApp?color=dc6c2c&logoColor=23272A&style=flat-square" alt="GitHub commits per month" />
    <img src="https://img.shields.io/github/repo-size/aiden2480/12A1-PizzaApp?color=fc7c04&logoColor=23272A&style=flat-square" alt="GitHub repo size" />
    <a href="https://aiden2480.github.io/12A1-PizzaApp/" target="_blank">
        <img src="https://img.shields.io/badge/website-click%20here-7289DA?color=ffa004&logoColor=23272A&style=flat-square" alt="GitHub pages site" />
    </a>
</div>

## :bar_chart: Details
Aiden Gardner 12SDD6 Year 12 Term 1 PizzaApp assessment 2021.
A pizza ordering app written in visual basic .NET

## :new: Releases
Versions of this project are incremented using [`semantic versioning`](https://semver.org/). The most recent **stable** release can be found just under the `About` tab on this page, and is marked with the `Latest` tag. More releases are documented in the [`releases tab`](https://github.com/aiden2480/12A1-PizzaApp/releases), which includes unstable releases (marked with the orange `Pre-release` tag).
The repository can be viewed at each point in time, and all stable versions, and most unstable versions have the compiled binary attached, although the source code is still provided.

## :confused: Issues
Known bugs are documented in the [issues tab](https://github.com/aiden2480/12A1-PizzaApp/issues?q=is%3Aissue). As it stands, the issue tab contains:
- [x] [#1 Pizza cost is rounded off](https://github.com/aiden2480/12A1-PizzaApp/issues/1)
    - The wrong datatype was being used to store the order cost, which resulted in a logic error where rounding occured where it was not wanted.

## :memo: Future features
- [ ] Validate fields as the user types
- [ ] Fill out toppings based on an option select to prefill a pizza type e.g. Hawaiian
- [ ] Add sides/drinks/dessert
- [ ] Add colour scheme
- [ ] Set window icon to pizza image
- [ ] Add patch version to each release, recompile binaries, and reupload to github.
- [ ] Add an attribute of `PizzaOrder` that displays the total cost of the order in the orders list
- [ ] Able to tick off each order as already delivered
- [x] Separate branch for editing the website
    - [website branch](https://github.com/aiden2480/12A1-PizzaApp/tree/website)
- [x] Generate links for each of the versions via JavaScript rather than hard coded.
    - Added in commit `ad5555a` and [PR #2](https://github.com/aiden2480/12A1-PizzaApp/pull/2)
