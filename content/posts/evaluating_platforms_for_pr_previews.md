---
title: "Evaluating Platforms for PR Previews: A Look at Vercel, Netlify, and AWS Amplify"
date: 2023-07-24T18:20:01+02:00
draft: false
---


As developers, we are always looking for solutions that enhance our workflows and increase productivity. One such solution is the ability to have a unique preview URL for each pull request (PR). It not only streamlines the code review process but also ensures the changes look good in a production-like environment before they are merged to the main branch. This feature is increasingly being offered by various platforms, which brings us to the topic of today's blog: comparing popular tools that offer separate preview URLs for each PR.

## Vercel

[Vercel](https://vercel.com/pricing) is a cloud platform designed for front-end developers and designers, making it an attractive option for staging and production. One of its most sought-after features is the creation of unique preview URLs for each PR. However, to unlock this functionality, users must upgrade to the Pro plan which costs $20 per user per month. 

Vercel is a robust solution for teams that want to rapidly build, preview, and ship web applications. However, keep in mind that the free plan only allows access to two team members.

## Netlify

Next in line is [Netlify](https://www.netlify.com/pricing/), another stellar platform that offers a Git-based workflow. Similar to Vercel, Netlify allows every PR to trigger a deployment. Their pricing starts at $19 per member per month, with only one team member allowed on the free plan. 

Netlify is a reliable choice for automating web projects and can be especially useful for small teams or individual developers.

## AWS Amplify

Third on the list is [AWS Amplify](https://aws.amazon.com/amplify/pricing/), a development platform from AWS for building and deploying web applications. Amplify, like the above options, provides unique URLs for each PR created on GitHub. The payment structure for AWS Amplify is a "pay-as-you-go" model, which might be more affordable depending on your usage. Notably, the first 12 months are free.

AWS Amplify is a versatile solution with a rich set of features, making it a robust choice for developers already operating in the AWS ecosystem.

## AWS Service Combination

AWS also offers the option to manually set up unique URLs for each PR by combining several of its services including S3, CloudFront, CodePipeline, CodeBuild, Lambda, and Route 53. While this gives a highly customized and potentially cost-effective solution, it is more complex and requires ongoing maintenance. A glitch in any one of these interconnected services could disrupt the entire process. Hence, I generally recommend sticking with AWS Amplify unless you have a compelling reason to opt for a custom solution.

## Comparison & Conclusion

Each of the above tools offers the ability to deploy each feature branch into a separate, isolated environment for preview. While they have generally similar features, the deciding factor for your team might come down to the cost. Below is a quick summary of the pricing:

- **Vercel:** $20 per user / month, with free plan access limited to 2 people
- **Netlify:** $19 per member / month, with free plan access limited to 1 person
- **AWS Amplify:** Pay-as-you-go model, with first 12 months free

Each of these options has its own unique strengths and pricing structure, so the optimal choice depends on your team's specific needs and budget. Make an informed decision based on your use-case, project requirements, team size, and, of course, budget. Happy coding!

