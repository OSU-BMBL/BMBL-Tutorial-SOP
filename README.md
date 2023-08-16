# BMBL tutorial SOP

Standard Operating Procedure (SOP) for Updating Tutorials using ChatGPT.

## Introduction

To ensure that our package remains user-friendly and is accompanied by an up-to-date tutorial, we're introducing a systematic approach to leverage the capabilities of ChatGPT, specifically GPT-4. This will enable us to enhance our tutorials and README files efficiently.

## Process

### Step 1: Upgrade Tutorials using ChatGPT

All first authors should utilize ChatGPT to enhance their respective tutorials. Given the superior capabilities of GPT-4, it will:

- Ensure a smooth user flow.
- Provide contextually relevant suggestions.
- Enhance the overall clarity and effectiveness of the tutorial.

**Usage Prompt for ChatGPT**:

```markdown
You are a technical writing expert in writing software tutorials. We're preparing to release a new version of our software and we need to update the README. Here's the current README. Please note down the changes required in markdown and embed the text in code chunks, so it won't convert to HTML in the assistant. Please review and provide a better version of the tutorial with any changes you think necessary to be added in a tutorial. After you've made the changes, please share the updated README in a markdown embedded in code chunks format.
```

Current README:
```markdown
Paste your tutorial within here.
```


### Step 2: Obtain Suggestions for Additional Sections

After obtaining a refined version of the tutorial, it's important to identify any missing sections or areas of improvement. For this, prompt ChatGPT as:

```markdown
can you provide suggestions of what are missing to be added in the tutorial?
```

To demonstrate, here's an example of what ChatGPT suggested for improvements in the MarsGT README:

- Quick Start Guide: Introduce a guide for users to get started swiftly.
- Updated Requirements: Update any software or hardware requirements, if necessary.
- Detailed Explanation of Features: Elaborate on the software's main features.
- Troubleshooting Section: Address common errors or problems.
- Contributing Guidelines: For open-source projects, specify how others can contribute.
- Additional Examples: Provide more real-world usage examples.
- Citation Information: Include citation details if the software is associated with a - publication.
- Version History or Changelog: Detail updates and changes of each software version.
- Contact Information: Offer a mode for users to get in touch.
- License Information: Clearly state the licensing terms.

## Conclusion

By following this SOP, we aim to consistently maintain high-quality, user-centric documentation that not only guides users effectively but also addresses common challenges and queries they might have.


---

You can adapt this template for your specific needs or context. The use of steps, bolding, and specific sections helps in making the document structured and easy to follow for readers.

Acknowledgements: 

Maintainer: [Cankun Wang](https://github.com/Wang-Cankun)

Contributors:

- [Cankun Wang](https://github.com/Wang-Cankun)