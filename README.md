# HackBaltimore

The HackBaltimore website is statically generated using jekyll and GitHub pages.

This README assumes that the reader has previous knowledge and experience using Ruby on Rails, jekyll, GitHub pages, JSON, and related web dev technologies.

To edit the website locally you must first:
1. Get Ruby running on your computer
1. Make sure you have bundler. You can try: `gem install bundler`
1. Clone this repository
1. Make sure you have all the latest gems, e.g. via `bundle install`

To review edits you make before committing them:
1. bundle exec jekyll serve
1. http://localhost:4000/

# JSON Files
There are a number of data files that populate the content of the site. The JSON files and their expected formats/inputs are described here.

## Mentors: _data/mentors.json
```javascript
{
  "image": "images/areas-mentors02.png",
  "name": "Lisa Dixon",
  "title": "CIO at Widgets Inc",
  "description": "Enter a bio for the mentor here",
  "facebook": "#",
  "instagram": "#",
  "linkedin": "#"
}
```

## Teams: _data/teams.json
```javascript
{
  "name": "Ravens",
  "image": "images/ravens.png",
  "captain": "Terrell Suggs",
  "members": [
    "Javorius Allen",
    "Mark Andrews",
    "Anthony Averett",
    "Chris Board",
    "Tyus Bowser",
    "Nick Boyle",
    "Bradley Bozeman",
    "Orlando Brown"
  ]
}
```

## Challenges: _data/challenges.json
```javascript
{
  "name": "Housing",
  "title": "Equitable Housing for All",
  "description": "Baltimore City faces a shortage of affordable housing.",
  "focus": "Housing",
  "organization": "HUD",
  "contact": "Terrell Suggs",
  "contact_phone": "+1-(540)-555-4000",
  "contact_email": "terrell@example.com"
}
```

## Organizers: _data/organizers.json
It is assumed that all organizers' photos / images will be stored in `/images/organizers/`.
```javascript
{
  "name": "Barack Obama",
  "bio": "Barack Obama served as the 44th President of the USA."
  "image": "barack-obama.jpg"
}
```

## Ideas: _data/ideas.json
```javascript
{
  "name": "Equitable Housing for All",
  "focus": "Housing"
  "problem": "Baltimore City faces a shortage of affordable housing."
  "solution": "Enter a solution to the problem here"
  "value": "Explain why the idea and solution matter here"
  "documentation": "examplelink.com supports my idea by providing research into the problem"
}
```
