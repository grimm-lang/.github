# Welcome to Grimm!

Hi!:wave: Thanks for discovering our project. I would like to walk you through the overall ideas and major goals of Grimm, and hope you find interest in what we are doing.

We make thousands of network requests in our applications every day. While each mainstream programming language has its own networking libraries, they are far from unified. We propose that a specially designed language can be used to cover all networking procedures, and can greatly improve productivity of web-related programming occasions, such as API calling, web scraping, etc.

***Scenario one: multi-platform applications***

Imagine you are writing an application that should work on Android, iOS and Windows, which shares the same web API across all platforms. Implementing identical networking procedures thrice in Kotlin, Swift and C# is definitely a repetitive job, and here is where Grimm comes to rescue. With a language tailored for web programming, along with bridging modules linking to the mainstream languages, much effort will be saved.

***Scenario two: web scraping***

While web scraping is a popular skill nowadays, the techniques can be quite daunting for startups: typically, they have to study using pip, requests and beautifulsoup, not to mention that some might get stuck executing `pip install`. Even for old hands, analyzing websites and collecting valuable elements can be a tedious job. Hopefully, with Grimm and the analytical tools it provides, web scraping will become much easier.

---

The Grimm project is more than designing a domain specific language, but should achieve the following goals in order to serve a more general purpose:

- **Implement bridging modules** with mainstream languages

- **Optimize language design** for networking procedures

- **Support** **modularity** to make Grimm scripts reusable

- **Build developer tools** to simplify coding and debugging

- **Comply with web spider drivers** like Selenium to unlock advanced usages

- **Handle typical authentication methods** to simplify login procedures

- **Allow hot-swapping** so that client-side upgrades due to server-side API changes can be avoided

- **Offer parallel programming support** for industrial web scraping applications

---

Grimm is a comprehensive project and contains the following repositories:

- [.github](https://github.com/grimm-lang/.github): community health repository of the GitHub organization

If you have any questions or ideas, do feel free to discuss them!
