# Hacktoberfest x ReactPlay

This repository contains a record of all low-code and no-code contributions made during the Hacktoberfest event in the ReactPlay community.

## What is Hacktoberfest

Hacktoberfest is a virtual event organized by DigitalOcean and its partners throughout October. It is aimed toward open source and introducing it to as many developers as possible. Anyone regardless of their programming experience are encouraged to contribute to open-source.

🔗 Read more [here](https://blog.reactplay.io/hacktoberfest-101-with-reactplay).

## No-code/Low-code Contributions

Until last year, hacktoberfest contributions were only valid for coding or maintaining a project. Since this year, Hacktoberfest has also been allowing low-code and no-code contributions.  
Here's the table that explains some of the ways of no-code/low-code contributions.

| Contribution Type | Low-code                                            | No-code                                       |
| ----------------- | --------------------------------------------------- | --------------------------------------------- |
| Writing           | Technical Documentation                             | Translating, Copy editing                     |
| Design            | Testing                                             | UX Testing, Graphics design, video production |
| Advocacy          | Talks, presentations, blogs, podcasts, case studies | social media blog posts                       |

🔗 Read more [here](https://blog.reactplay.io/hacktoberfest-101-with-reactplay#heading-new-changes-introduced-this-year).

## Hacktoberfest with ReactPlay

We are already having active code contributions in our [main project](https://github.com/reactplay/react-play). However, if you have contributed to us in some other way, you need to submit it in this repository.  
The valid contributions will be merged to the repository with `hacktoberfest-accepted` tag.

## What Are Valid Contributions

Anything that you have done that helps the ReactPlay community to grow, and improve in either low-code or no-code categories will be considered as a valid contribution. You need to provide detailed informaton about the contribution along with a URL that validates your contribution.

## How to Submit Your Contribution

1. Go to the [Issues](https://github.com/reactplay/hacktoberfest/issues/new/choose) section of the repository and add a new issue with **New Contribution** template

	![issues](https://user-images.githubusercontent.com/53049546/193395979-38a09dae-a057-4e3e-bcfb-20475b0f47bf.png)

2. Fill in the required details with appropriate information. And then Submit the issue.
3. Wait until someone from the community assigns you to the issue.
4. Fork this repository in your own account once you are assigned to the issue.

   ![fork](https://user-images.githubusercontent.com/53049546/193394469-43960255-6ad3-443d-872d-024bc552da3c.png)

5. Create a new branch with your github username.

   ![new-branch](https://user-images.githubusercontent.com/53049546/193394454-afb7c208-188e-40c5-9a6a-b8e27344b27d.png)

6. Inside `/data` directory in the root folder, open the `json` file named with current year (eg: `2022-contributions.md`) .
7. Use your github username as a key and use the following template to add your data.
   ```json
   {
     "username": {
       "name": "<Your name>",
       "username": "<GitHub username",
       "category": "<code | no-code | low-code>",
       "type": "<design | writing | advocacy>",
       "contribution": "<docs | translating | copy-editing | testing | UX-testing | design | video | talks | presentations | workshops | case-studies | thread | podcasts | blogs>",
       "description": "<explain what you did within 280 characters>",
       "link": "<url to validate your contribution>"
     }
   }
   ```
8. Once you are finished, commmit your changes.

   ![commit](https://user-images.githubusercontent.com/53049546/193394645-6f83839e-659c-4626-9e16-199a04c06105.png)

9. Go to the `Code` section of the repository. You will see a yellow box asking you to compare & create a pull request, click it.

   ![image](https://user-images.githubusercontent.com/53049546/193394767-199612ee-416c-40fd-89b9-4516797d3902.png)

10. If the above step doesn't work, go to `Pull Request` section and createa a new request.
11. Select the `main` branch of `reactplay/hacktoberfest` repository, and solve merge conflicts if any.
12. Wait until someone from our team approves it.

## Example

```json
{
  "joshi-kaushal": {
    "name": "Kaushal Joshi",
    "username": "joshi-kaushal",
    "category": "no-code",
    "type": "writing",
    "contribution": "blogs",
    "description": "I wrote a blog discussing why reactplay is cool",
    "link": "https://blog.kaushaljoshi.dev"
  }
}
```

## Get in Touch
If you are stuck somewhere, or have some doubts; join our [Discord server](https://discord.com/channels/982239924227031070/983209230729379901) and mention it there. 
