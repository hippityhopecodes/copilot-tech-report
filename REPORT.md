# GitHub Copilot - Technology Report

```
Logan Crisp, Trevor Harless, Hope Spence (3/16/2025)
```
This report provides an introductory evaluation of GitHub Copilot to assess its potential
application at CodeFlow Solutions. By analyzing multiple sources, it examines the technology’s
capabilities, benefits, drawbacks, and overall suitability for our development processes. The goal
is to offer a well-rounded assessment that informs whether further investigation, such as a
feasibility study, is warranted.

**Summary 2
Description 2**
Key Features 2
How It Works 3
**Applications 3**
Company Integrations 4
Field Experiments 4
**Competing Technologies 4
Relative Advantages & Disadvantages 5**
GitHub Copilot 6
Amazon Q Developer 7
ChatGPT 8
Summary 9
**Conclusion 9
References 10**


## Summary

This report analyzes GitHub Copilot’s capabilities, examines its applications in the industry, and
compares it to competing technologies. Our findings suggest that GitHub Copilot best aligns
with the needs of our small development team and integrates into our workflow more easily.
Field experiments show that companies such as Microsoft and Accenture have successfully
integrated GitHub Copilot into their developers' workflows and have seen significant
improvements. While there are concerns about overreliance and occasional AI-generated errors,
GitHub Copilot provides a cost-effective solution to scaling development without increasing
headcount. Based on these findings, we should further investigate GitHub Copilot adoption,
incorporating A/B testing and developer feedback to evaluate its effectiveness.

## Description

**GitHub Copilot** is an AI-driven coding assistant designed to help developers with coding tasks,
improve productivity, and refine code quality. It is a multifunction tool that can act as a code
reviewer, documentation assistant, and rubber duck, as well as perform a multitude of other
functions. This makes it a potential replacement for tools like debuggers or practices such as pair
programming.

#### Key Features

```
● AI Model Selection: Users can switch between different AI models, including
Anthropic’s Claude 3.5 Sonnet, OpenAI o3, and GPT-4o
● Agent Mode: In agent mode, GitHub Copilot can gather information across multiple files,
suggest and test edits, and then validate its changes for developer approval.
● Edit Suggestions: Predicts and adapts to a developer's workflow by offering
context-based suggestions.
● Code Review Assistance: Developers can ask GitHub Copilot to review their code,
uncover bugs, fix mistakes, and refine code quality.
● Third-Party Integrations: GitHub Copilot Chat integrates with various third-party tools
and services through extensions.
● Terminal Assistance: Developers can receive help with specific commands and actions
directly in the terminal.
● Mobile App Support: Copilot is available on mobile devices.
```

#### How It Works

GitHub Copilot is powered by generative AI models developed by GitHub, OpenAI, and
Microsoft. It has been trained on natural language text and code from publicly available sources,
including public GitHub repositories.

_Figure 1: GitHub Copilot Operational Flow (source)_
Copilot integrates smoothly with various Integrated Development Environments (IDEs), such as
Visual Studio Code, Xcode, and JetBrains, and supports all programming languages that appear
in public repositories.
For detailed videos and images, visit the GitHub Copilot Features Page.

## Applications

Many of our customers’ web applications follow similar architectural patterns and may contain
the same elements; by utilizing GitHub Copilot, our engineers could reduce the amount of time
spent on redundant code generation. GitHub Copilot can also be used to improve code quality
and consistency by enforcing best practices, which often leads to less technical debt. It
significantly reduces debugging time by identifying errors and suggesting fixes, which
minimizes the need to search documentation or online resources. GitHub Copilot can also
automatically generate function descriptions, README files, and other documentation, which
saves time and reduces stress for developers.


#### Company Integrations

Many companies have integrated GitHub Copilot into their workflows to enhance developer
efficiency. For example, Mercedes-Benz utilized it to improve collaboration and efficiency for
their developers in the automotive industry, while Duolingo used it to enforce code consistency
and improve developer speed in the mobile app industry. GitHub has highlighted its impact
across different companies in their case studies and blog posts.

#### Field Experiments

GitHub Copilot has been tested in both laboratory and field experiments. Although laboratory
experiments are useful, we can gauge how the tool performs in the real world by focusing on
field experiments.

```
● A study was conducted by GitHub to measure the impact on Accenture’s development
workflow after the use of GitHub Copilot. They found that developers delivered projects
faster by spending less time debugging, which ultimately accelerated time to market. This
is particularly relevant for our developers since reducing debugging time would allow our
small team to focus on delivering high-quality features.
● In a recent field experiment from February 2025 , it was found that developers from
Microsoft, Accenture, and an anonymous Fortune 100 company saw a 26.08% increase in
completed tasks after the use of GitHub Copilot. This suggests that adopting GitHub
Copilot could lead to a significant boost in developer efficiency which helps our team
complete more projects without increasing headcount.
```
## Competing Technologies

GitHub Copilot is one of several different tools created for software development environments,
with Amazon Q Developer and ChatGPT being popular alternatives. While all three of these
tools were released relatively close to each other, there are a multitude of differences.

ChatGPT is a general-purpose AI chatbot with coding capabilities but lacks direct IDE
integration and customization. ChatGPT primarily functions as a language model, unlike GitHub
Copilot and Amazon Q Developer, which are built specifically for software development. While
it can assist with code generation and debugging, it does not support platform-specific
integrations like GitHub or AWS.

Amazon Q Developer is an AI-powered assistant designed for software engineering, similar to
GitHub Copilot, but with a stronger focus on AWS integration. It offers AWS-specific features


like cloud service automation and troubleshooting, making it more tailored to AWS
environments than general-purpose coding assistants.

AI coding assistants do not replace any single tool but may reduce the need for pair
programming, extensive manual debugging, and hiring additional developers. They can also
lessen reliance on code search tools, autocomplete extensions, and some aspects of traditional
integrated debugging features.

## Relative Advantages & Disadvantages

To evaluate between traditional pair programming and the code generation tools, the following
criteria should be considered:
● **Code Quality & Accuracy:** Does the code correctly solve the problem? Is the code up to
quality standards?
● **Security:** Does the code expose any security vulnerabilities?
● **Productivity:** Are developers more efficient?
● **Workflow Integration:** Does it work well within our development environment?
● **Cost:** Is it affordable?


### GitHub Copilot

**Advantages Disadvantages
Code Quality & Accuracy:**
From this study, it was found that the quality of code written by
GitHub Copilot was objectively better than code written without it.
Code was more functional, easier to read, and more likely to be
approved.

**Security:**
Has many policies and settings to ensure best practices are being
followed.

**Productivity:**
From a 2022 study, it was found that developers experienced
improved satisfaction and completed a software related task 55%
faster. In general, developers perceive their productivity to be
increased after the integration of GitHub Copilot.

**Workflow Integration:**
● Since we use GitHub to house all of our projects, Copilot fits
into our workflow smoothly.
● Integrates into VS Code, our primary IDE.
● Many customization options.

**Cost:**
$39/mo per user for their Enterprise plan. More details here.

```
Security :
Note on Security
Productivity:
Note on Productivity
```

### Amazon Q Developer

**Advantages Disadvantages
Code Quality & Accuracy:**
An acceptance rate of up to 37% of suggestions from a
BT Group report in 2024.

**Security:**
Includes a feature which will scan for vulnerabilities
& autocreate tests, but cannot guarantee complete
coverage.

**Productivity:**
Developers were quoted experiencing up to a 40%
increase in productivity. However, this was seen when
companies already utilized AWS.

**Workflow Integration:**
● Integrates into VS Code, our primary IDE.
● Many customization options.

**Cost:**
$19/mo per user, more details here.

```
Security:
Note on Security
Productivity:
Note on Productivity
Workflow Integration:
Optimized for AWS environments,
meaning our company, which uses
many cloud providers, may face
integration challenges.
```

### ChatGPT

```
Advantages Disadvantages
Code Quality & Accuracy:
Excellent at generating correct responses
to simple coding tasks. (Zhan Shu et al.,
Ranim Khojah et al.)
Security
Enterprise plans exclude customer data
from training, provide enterprise-grade
controls, and enhance security with
API-level protections.
Productivity
Several studies indicate an overall
increase in developer productivity:
● Development time was reduced by
up to 73% in some cases compared
to manual coding in this study.
● Countries with ChatGPT access
saw about 645 more GitHub
pushes per 100,000 people in this
analysis.
● 50% of participants said ChatGPT
reduced repetitive tasks in this
study
```
```
Code Quality & Accuracy:
Unable to generate correct responses for more
complex coding tasks.(Zhan Shu et al., Ranim
Khojah et al.)
Security
● Note on Security
● This study found that ChatGPT-generated
code was not always optimized for security,
with vulnerabilities related to user input
handling and data queries.
Productivity
Note on Productivity
Cost:
No specific price is given for the enterprise plan.
Only has custom pricing based on the company.
Workflow Integration:
● ChatGPT does not natively integrate with
IDEs or provide specialized support for tools
like GitHub or AWS.
● Does not offer many customization options
```
#### Note on Security

Since suggestions are only as good as the data that they are trained on, there will always be
security risks because data models cannot keep up with the latest attack techniques.

#### Note on Productivity

An overreliance on AI can occur in developers, as spoken of in this article subsection,
“Mitigating the potential risks of AI in software development” from IBM. Overreliance could


lead to deteriorating critical thinking and problem solving skills. Furthermore, there is a balance
between the speed at which a developer can write code and the speed at which a developer can
review code generated by an AI, where the latter seems to be more efficient.

#### Summary

GitHub Copilot has strong evidence of increased code quality and productivity while still being
secure. Amazon Q Developer offers similar advantages to GitHub Copilot and has lower pricing,
but it is primarily useful for developers in AWS environments. ChatGPT has similar benefits and
drawbacks to its competitors but lacks IDE integration and specialized workflow support.
Although each tool has inherent drawbacks, GitHub Copilot integrates with our existing
GitHub-based workflow, unlike Q Developer and ChatGPT.

## Conclusion

Based on our research, GitHub Copilot stands out as the most secure and effective AI assistant
for our development environment, integrating with our existing GitHub workflow. In contrast,
Amazon Q Developer is tailored for AWS, while ChatGPT lacks direct integration capabilities
and is already part of Copilot’s underlying technology. Given our reliance on GitHub and the
need for cloud flexibility, Copilot’s broader compatibility makes it the best fit for our needs.

The cost of GitHub Copilot Enterprise is **$57,564 annually** for our 123 employees. This cost is
significantly lower than hiring additional employees to improve company-wide productivity.
Additionally, the Enterprise plan provides crucial security and administrative controls. These
controls ensure that Copilot is used securely across our teams, reducing risks associated with
AI-generated code and maintaining a high standard of development integrity.

To determine whether the benefits are readily recognizable, A/B testing could be conducted to
measure productivity gains and development speed improvements. Additionally, collecting
qualitative feedback from our developers on workflow integration could provide tailored insights
into their experience.

Despite concerns about overreliance and potential inaccuracies, research shows that GitHub
Copilot delivers significant productivity gains at a manageable cost. With its integration
capabilities and security features, it stands out as the best choice for our company. Based on
these findings, exploring its adoption within our development teams is worthwhile


```
References
```
Amazon. (n.d.). _AI for software development - Amazon Q developer customers - AWS_. Amazon
Web Services, Inc. Retrieved March 16, 2025, from
https://aws.amazon.com/q/developer/customers/
Bauer, J. (2024, November 18). _Does GitHub Copilot improve code quality? Here’s what the
data says_. The GitHub Blog.
https://github.blog/news-insights/research/does-github-copilot-improve-code-quality-here
s-what-the-data-says
_BT Group advances AI-enhanced product development with Amazon CodeWhisperer_. (n.d.). BT
Group Advances AI-Enhanced Product Development with Amazon CodeWhisperer.
https://newsroom.bt.com/bt-group-advances-ai-enhanced-product-development-with-ama
zon-codewhisperer/
Chatgpt. (n.d.-a). https://openai.com/chatgpt/
Cui, Z., Demirer, M., Jaffe, S., Musolff, L., Peng, S., & Salz, T. (2024). _The Effects of Generative
AI on High Skilled Work: Evidence from Three Field Experiments with Software
Developers_. https://doi.org/10.2139/ssrn.

GeeksforGeeks. (2024, June 20). _What is pair programming?_
https://www.geeksforgeeks.org/pair-programming/

_GitHub copilot · your AI pair programmer_. GitHub. (n.d.-a). https://github.com/features/copilot

_GitHub’s success stories_. GitHub. (n.d.-b).
https://github.com/customer-stories/all?feature=GitHub%2BCopilot#browse


_How duolingo uses github_. GitHub. (n.d.-c). https://github.com/customer-stories/duolingo

_How Mercedes-Benz uses GitHub_. GitHub. (n.d.-d).
https://github.com/customer-stories/mercedes-benz

Ibm. (2025, January 7). _What is a chatbot?_. IBM. https://www.ibm.com/think/topics/chatbots

Impact of the availability of CHATGPT on software development activity. Development Data
Partnership. (n.d.).
https://datapartnership.org/updates/impact-of-the-availability-of-chatgpt-on-software-dev
elopment/

Kalliamvakou, E. (2022, September 7). _Research: quantifying GitHub Copilot’s impact on
developer productivity and happiness_. The GitHub Blog.
https://github.blog/news-insights/research/research-quantifying-github-copilots-impact-o
n-developer-productivity-and-happiness/
Khojah, R., Mohamad, M., Leitner, P., & de Oliveira Neto, F. G. (2024). Beyond code
generation: An observational study of CHATGPT usage in software engineering practice.
Proceedings of the ACM on Software Engineering, 1(FSE), 1819–1840.
https://doi.org/10.1145/
Lewkowicz, J. (2021). GitHub Copilot Operational Flow. GitHub Copilot aims to help
developers write better code. SDTimes. Retrieved March 16, 2025, from
https://sdtimes.com/softwaredev/github-copilot-aims-to-help-developers-write-better-cod
e/.
_Managing policies and features for Copilot in your enterprise - GitHub Enterprise Cloud Docs_.
(2025). GitHub Docs.


```
https://docs.github.com/en/enterprise-cloud@latest/copilot/managing-copilot/managing-c
opilot-for-your-enterprise/managing-policies-and-features-for-copilot-in-your-enterprise
```
Shashi16, Contributor, B., & 24, A. (2023, April 20). _Chatgpt- what? why? and how?: Microsoft
Community Hub_. TECHCOMMUNITY.MICROSOFT.COM.
https://techcommunity.microsoft.com/blog/educatordeveloperblog/chatgpt--what-why-an
d-how/

Shu, Z., & Dong, Z. (2025). A Study of Web Code Generation Based on ChatGPT.
https://doi.org/10.4108/eai.21-11-2024.

_Subscription plans for GitHub Copilot - GitHub Docs_. (2024). GitHub Docs.
https://docs.github.com/en/copilot/about-github-copilot/subscription-plans-for-github-cop
ilot

Wikimedia Foundation. (2025, February 19). _Rubber duck debugging_. Wikipedia.
https://en.wikipedia.org/wiki/Rubber_duck_debugging

Ya Gao, G. C. R. (2024, May 13). _Research: Quantifying github copilot’s impact in the
enterprise with Accenture_. The GitHub Blog.
https://github.blog/news-insights/research/research-quantifying-github-copilots-impact-in
-the-enterprise-with-accenture/


