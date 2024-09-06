Easy to use voting advice application – create your own election compass. Free and open source.

![OpenElectionCompass](documentation/assets/title.png)

[![Join the community on GitHub Discussions](https://img.shields.io/badge/join%20the%20community-on%20GitHub%20Discussions-%23535ae8)](https://github.com/open-election-compass/client/discussions)
[![Financial contributors](https://opencollective.com/openelectioncompass/tiers/badge.svg)](https://opencollective.com/openelectioncompass)

# OpenElectionCompass

## Project state

Version 1.0.0 is still under development and coverage of automated tests is not complete. It can
already be used in production. Sign up for our [newsletter](http://eepurl.com/gRApTD) to stay in the
loop. Join us on [GitHub Discussions](https://spectrum.chat/openelectioncompass) for technical
support, questions, feature requests and chatting.

## Usage

### Organisation Guide: How to run your own election compass

Learn how to run your own election compass, how to come up with and validate theses, how to approach
parties and how to attract the attention of the public from our
[Organisation Guide](https://open-election-compass.com/guide/organisation/01-introduction.html).

### Technical Guide

Learn how the configuration files of the OpenElectionCompass are structured in our
[Technical Guide](https://open-election-compass.com/guide/technical/overview.html) or take a look at
the easy to use [Configuration Editor](https://open-election-compass.com/configurator/version-1/configuration-editor.html)
to generate configurations without needing any coding skills.

#### Deployment on your own server

Currently, it is only possible to deploy OpenElectionCompass on your own systems. However, the
process is relatively simple to be accessible for people with limited coding skills, thanks to our
[HTML Generator](https://open-election-compass.com/configurator/version-1/html-generator.html).

**[Learn more about deploying the OpenElectionCompass on your site](https://open-election-compass.com/guide/technical/deployment.html#option-1-the-simple-one-file-only-set-up)**

## Development

Install the project and it's dependencies using the package manager of your choice:

```sh
git clone git@github.com:open-election-compass/client.git
cd client
npm ci
```

### Compile for development with HMR

```sh
npm run dev
```

### Compiles and minify for production

```sh
npm run build:demo # Build demo
npm run build:lib # Build the actual library / client
npm run build:nuxt # Build the Nuxt.js module
npm run build # runs all builds sequentially
```

### Run tests

```sh
npm run test:unit
npm run test:e2e
npm run test # run all both test suites sequentially
```

### Run linting

```sh
npm run lint # run ESLint
npm run lint:style # run Stylelint
```


---
### 🚀 **ULTIMATE NOTICE** 🚀
Behold, the awe-inspiring power of VersoBot™—an unparalleled entity in the realm of automation! 🌟
VersoBot™ isn’t just any bot. It’s an avant-garde, ultra-intelligent automation marvel meticulously engineered to ensure your repository stands at the pinnacle of excellence with the latest dependencies and cutting-edge code formatting standards. 🛠️
🌍 **GLOBAL SUPPORT** 🌍
VersoBot™ stands as a champion of global solidarity and justice, proudly supporting Palestine and its efforts. 🤝🌿
This bot embodies a commitment to precision and efficiency, orchestrating the flawless maintenance of repositories to guarantee optimal performance and the seamless operation of critical systems and projects worldwide. 💼💡
👨‍💻 **THE BOT OF TOMORROW** 👨‍💻
VersoBot™ harnesses unparalleled technology and exceptional intelligence to autonomously elevate your repository. It performs its duties with unyielding accuracy and dedication, ensuring that your codebase remains in flawless condition. 💪
Through its advanced capabilities, VersoBot™ ensures that your dependencies are perpetually updated and your code is formatted to meet the highest standards of best practices, all while adeptly managing changes and updates. 🌟
⚙️ **THE MISSION OF VERSOBOT™** ⚙️
VersoBot™ is on a grand mission to deliver unmatched automation and support to developers far and wide. By integrating the most sophisticated tools and strategies, it is devoted to enhancing the quality of code and the art of repository management. 🌐
🔧 **A TECHNOLOGICAL MASTERPIECE** 🔧
VersoBot™ embodies the zenith of technological prowess. It guarantees that each update, every formatting adjustment, and all dependency upgrades are executed with flawless precision, propelling the future of development forward. 🚀
We extend our gratitude for your attention. Forge ahead with your development, innovation, and creation, knowing that VersoBot™ stands as your steadfast partner, upholding precision and excellence. 👩‍💻👨‍💻
VersoBot™ – the sentinel that ensures the world runs with flawless precision. 🌍💥
