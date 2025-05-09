# LinkFree - EddieHub

LinkFree Connect audiences to all of your content with just one link. It is an open-source alternative to [Linktree](https://linktr.ee/) implemented in JavaScript. It was initially created on a YouTube [live stream](https://www.youtube.com/watch?v=Jorl_vcp-Ew).

![Screenshot](https://user-images.githubusercontent.com/60853067/133296120-dbdb1799-4cca-4708-81ce-05edc65e59c9.png)

> A note for Hacktoberfest Participants:
> 
> Pull requests which add or edit your information in a `data/${yourname}.json` file will NOT be counted for Hacktoberfest.
>
> Pull requests which improve the codebase, documentation, or other aspects of the project and are in line with the core values
> of the event will be counted - maintainers will opt in these PRs by applying the `hacktoberfest-accepted` label.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/EddieHubCommunity/LinkFree)

## 👨‍💻 Demo

Check out the website : [LinkFree](http://linkfree.eddiehub.org/)

## 👇 Prerequisites

Before installation, please make sure you have already installed following tools:

- [Git](https://git-scm.com/downloads)
- [NodeJs](https://nodejs.org/en/download/)

## 🛠️ Installation Steps

1. Fork the project
2. Clone the project
3. Navigate to the project directory `cd LinkFree`
4. Install dependencies with `npm install`
5. Run `npm start`
7. Optional : Run the tests with `npm run cypress:run`

Alternatively, skip all the steps by using [![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/EddieHubCommunity/LinkFree/)

## 👨‍💻 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.
Check out [Contributing.md](Contributing.md) file for more information.

### 🎭 To Add Your Profile

Create a file named `your-username.json` in the directory `public/data` with the following content:

Optional fields: `links` and `milestones`

```json
{
  "name": "Eddie Jaoude",
  "bio": "Founder of EddieHub",
  "avatar": "https://github.com/eddiejaoude.png",
  "links": [
    {
      "name": "Follow me on GitHub",
      "url": "https://github.com/eddiejaoude",
      "icon": "github"
    },
    {
      "name": "Follow me on Twitter",
      "url": "https://twitter.com/eddiejaoude",
      "icon": "twitter"
    },
    {
      "name": "Learn more about Open Source on my YouTube channel",
      "url": "https://youtube.com/eddiejaoude",
      "icon": "youtube"
    }
  ],
  "milestones": [
    {
      "title": "Started Freelancing",
      "date": "May 2010",
      "icon": "dollar",
      "color": "grey",
      "description": "Started freelancing again",
      "url": "https://www.eddiejaoude.io/"
    },
    {
      "title": "Started YouTube",
      "image": "https://github.com/eddiejaoude.png",
      "date": "June 2019",
      "icon": "youtube",
      "color": "red",
      "description": "First real video",
      "url": "https://youtube.com/eddiejaoude"
    },
    {
      "title": "GitHub Star",
      "date": "2020",
      "icon": "github",
      "color": "green",
      "description": "Became a GitHub Star with 30 other people",
      "url": "https://github.com/eddiejaoude"
    },
    {
      "title": "GitHub Star of the Year",
      "date": "2020",
      "icon": "github",
      "color": "green",
      "description": "Won GitHub Star of the Year out of 55+ million people",
      "url": "https://github.com/eddiejaoude"
    }
  ]
}
```

Your URL will be `http://linkfree.eddiehub.org/<yourusername>`. For example: <http://linkfree.eddiehub.org/eddiejaoude>\
Your `avatar` URL should take the format of `https://github.com/<yourusername>.png`.

## 🛡️ License

This project is licensed under the MIT License - see the [`LICENSE`](LICENSE) file for details.

## 💪 Thanks to the all Contributors

Thanks a lot for spending your time in helping LinkFree grow. Thanks a lot! Keep rocking 🍻
[contributors](https://github.com/EddieHubCommunity/LinkFree/graphs/contributors)

## 🙏 Support

This project needs a ⭐️ from you. Don't forget to leave a star ⭐️
Awesome work Sir.
