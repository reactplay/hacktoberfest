# Hacktoberfest
This repository contains a record of all low-code and no-code contributions made during the Hacktoberfest event in the ReactPlay community.


## What is Hacktoberfest
Hacktoberfest is a virtual event organized by DigitalOcean and its partners throughout October. It is aimed toward open source and introducing it to as many developers as possible. Anyone regardless of their programming experience are encouraged to contribute to open-source.

🔗 Read more [here](https://blog.reactplay.io/hacktoberfest-101-with-reactplay).

## No-code/Low-code Contributions
Until last year, hacktoberfest contributions were only valid for coding or maintaining a project. Since this year, Hacktoberfest has also been allowing low-code and no-code contributions.  
Here's the table that explains some of the ways of no-code/low-code contributions.

| Contribution Type | Low-code | No-code |
| --- | --- | --- |
| Writing | Technical Documentation | Translating, Copy editing |
| Design | Testing | UX Testing, Graphics design, video production |
| Advocacy | Talks, presentations, blogs, podcasts, case studies | social media blog posts |

🔗 Read more [here](https://blog.reactplay.io/hacktoberfest-101-with-reactplay#heading-new-changes-introduced-this-year).

## Hacktoberfest with ReactPlay
We are already having active code contributions in our [main project](https://github.com/reactplay/react-play). However, if you have contributed to us in some other way, you need to submit it in this repository.  
The valid contributions will be merged to the repository with `hacktoberfest-accepted` tag.

## What Are Valid Contributions
Anything that you have done that helps the ReactPlay community to grow, and improve in either low-code or no-code categories will be considered as a valid contribution.  You need to provide detailed informaton about the contribution along with a URL that validates your contribution.  

## How to Submit Your Contribution
1. Fork this repository in your own account
2. Create a new branch with your github username
3. Inside `/data` directory in the root folder, open the `json` file named with current year (eg: `2022-contributions.md`) 
4. Use your github username as a key and use the following template to add your data
5. Once you are finished, commmit those changes
6. Go to the `Code` section of the repository. You will see a yellow box asking you to create a pull request, click it.
7. If the above step doesn't work, go to `Pull Request` section and createa a new request.
8. Select the `main` branch of `reactplay/hacktoberfest` repository, and solve merge conflicts if any.
9. Wait until someone from our team approves it.

## What to Put in the JSON file?
```json
<username>: {
    name: <Your name>,
    username: <GitHub username,
    category: <code | no-code | low-code>,
    type: <design | writing | advocacy>,
    contribution: <docs | translating | copy-editing | testing | UX-testing | design | video | talks | presentations | workshops | case-studies | thread | podcasts | blogs>
    description: <lorem ipsum within 280 characters>,
    link: <url to validate your contribution>,
},
```
