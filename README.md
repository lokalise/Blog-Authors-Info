# Lokalise Writing Guidelines

So, you decided to contribute to [Lokalise blog](https://lokalise.com/blog) — that's great! :punch: Here we've summed up the general requirements as well as useful tips.

## General Requirements

* Currently, we are interested in articles that revolve around internationalization/localization process (aka I18n and L10n). Ideally, these articles should be technical tutorials, but that's negotiable. If you have an interesting topic — don't hesitate to suggest it.
* :pencil: The article should be at the very least *1500* characters long but no longer than *5000* characters. 2500-3000 characters is ideal.
* The article should cover a single topic with all the necessary explanations. The reader should be able to apply the received knowledge into practice. Do not write just for the sake of hitting a given character limit.
* The article should be clearly structured.
* :ballot_box_with_check: The article should be proofread before sending for review.
* The article should contain relevant code samples with all necessary explanations. If you demonstrate the concepts by building a sample application, its source code should be publicly available on GitHub, Bitbucket, CodePen, or a similar service. A working demo is appreciated as well.
* The article is written exclusively for our blog. Reposts are not permitted without explicit approval from our side.
* The article should be written by you or your team — we take plagiarism very seriously.

## Style Guide

### Language

* :us: Your article should be written in US English.
* Do not use overly complex words and sentences — our readers have different levels of language proficiency. Divide long sentences into shorter ones. Everyone (with at least a basic understanding of English) should be able to get a grasp of your explanations.

### Tone and Narration

* The tone of the article should be friendly. You are not a strict mentor but rather a person who helps his/her colleagues to better understand a given topic. Adding a couple of appropriate jokes is okay too. On the other hand, don't get *too* informal:
  + :heavy_check_mark: The explanations should be confident, precise, clear, comprehensive, and fun.
  + :x: The explanations should not be overly pedantic, complicated, or patronising.
* In your explanations use words like "we" and "us" when appropriate (not "I" and "me"). You are solving the given task together with the reader:
  + :heavy_check_mark: Next *we* are going to install the following software...
  + :x: Next *I* am going to install the following software...
* Address the reader with the word "you":
  + :heavy_check_mark: I hope *you* found this article helpful and interesting!
  + :x: I hope *readers* found this article helpful and interesting!
* Explain complex terms. Provide links to relevant materials if needed.
* Use transition words: "first", "next", "lastly", "therefore", "so", and other.
* :no_mouth: Do not use slang and other inappropriate words (like swearing). Do not attack any groups of people or start holy wars ("Linux is better/worse than Windows").
* Do not use too many passive voice:
  + :heavy_check_mark: You should install the following software...
  + :x: The following software should be installed...
* Try to use gender-neutral phrases.
 
### Grammar and Spelling

* Do not forget to proofread the text (though the editor will double-check everything and make edits as necessary). You may use [grammarly.com](https://www.grammarly.com/) or a similar tool.
* Capitalize company names according to the company’s style.
* Use [Oxford comma](https://www.grammarly.com/blog/what-is-the-oxford-comma-and-why-do-people-care-so-much-about-it/):
  + :heavy_check_mark: Lock, stock, and two smoking barrels
  + :x: Lock, stock and two smoking barrels
* [Use dashes and hyphens properly](https://www.grammarly.com/blog/hyphens-and-dashes/).

### Sections and Subsections

* Give your article a logical structure by dividing it into sections and subsections (subtitles), for example:
  + Introduction
  + Prerequisites
  + Setting Up Sample Application
  + Explaining Feature A
  + Explaining Feature B
  + Conclusion
* The title of the article will be a heading level 1 (`h1`) which means that sections of the article should be `h2`-`h6`.
* Subtitles should not be longer than 5-6 words.
* The title as well as subtitles should be properly capitalized. You may use [capitalizemytitle.com](https://capitalizemytitle.com/) or a similar tool.

#### Bullets

Bullets is a great tool but don't forget to format them properly:

* Try to add an introductory sentence followed by a colon.
* Use a period after every bullet point that is a complete sentence.
* Use no punctuation after bullets that are not complete sentences.
* Capitalize the first letter of every bullet point that is a complete sentence.
* Do not capitalize the first letter of bullets that are not complete sentences.
* Use either complete sentences or fragments.

#### Links

* Avoid using phrases like "Click here" for a link. Try using more meaningful text:
  + :heavy_check_mark: Documentation for this method [can be found on the official website](http://example.com/)
  + :x: [Click here](http://example.com/) to find documentation for this method
* :link: Provide links to relevant resources (documentation, specifications) when explaining new terms and concepts.
* Giving links to other Lokalise articles is very much appreciated.
* On the other hand, do not overuse external links: for example, do not provide references for common knowledge. The provided links should be relevant to the main topic of the article.
* Never ever add sponsored or promotional links without agreeing with the editor. Such links will be removed.

#### Other Tips

* *Acronyms* should be explained unless they are well-known (like HTML or PNG).
* *Citations* should include the original sources.
* If you are using *images* from other sources, make sure you have permission to do so. We encourage authors to use original images.
* Provide `alt` text for your images.
* Do not use *smiles* and *emoticons*.
* Avoid using *complex contractions* like "could've":
  + :heavy_check_mark: We'll, isn't, hasn't, could have, would have
  + :x: Could've, should've, would've
* :exclamation: The name of our company is *Lokalise*. Not Localise, Localize, or Lokalize.

### Code Samples

#### Inline Code

* Inline code [should be formatted with backticks](https://confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html#Markdownsyntaxguide-Inlinecodecharacters).
* All variables, functions, methods, classes, filenames, directory names, accepted values, returned values, and similar constructs should be formatted as inline code when mentioned in the text:
  + "The function is `hello()`. It lives in the `Demo` class and return `"Hello"` as a result. The `Demo` class is defined in the `lib/demo` file."
 
#### Code Blocks

* Large code blocks should be presented with GitHub Gist, CodePen, or similar services. To insert GitHub Gist (also demonstrated in [this small video](https://drive.google.com/open?id=1hwnDVy8gYpFDUZnkprOr3_jW7R4sHNYg)):
  + Create a new [Gist](https://gist.github.com/)
  + Copy URL to your Gist, for example [https://gist.github.com/bodrovis/88b0c01eaf518917db80925b8db8cafb](https://gist.github.com/bodrovis/88b0c01eaf518917db80925b8db8cafb)
  + Paste URL to the text editor in our WordPress
  + The URL should be automatically converted to a code preview
* We also have a [Gist Press](https://github.com/bradyvercher/gistpress) plugin installed which allows to embed a specific file from the given Gist. To use it:
  + Insert `[gist id="9b1307f153f4abe352a4"]` shortcode into the editor where `id` is the ID of your Gist (provided in the Gist URL)
  + In order to embed a specific file, say `[gist id="9b1307f153f4abe352a4" file="media-control-snippet.php"]`
  + More information can be found in [the official documentation](https://github.com/bradyvercher/gistpress#shortcode)
* Indent and format your code properly making it easier to read.
* Make sure the code does not contain any errors or typos.
* Try not to use obscure techniques (aka "black magic"). If you must, explain this technique to the reader.
* If you are building a complex feature try to move step-by-step gradually increasing complexity. Do not throw a huge code sample at the reader trying to explain everything in one go.
* If the code sample has multiple important lines, mark them in the code with the comments and then explain each line separately. For example:

```ruby
a = 1     # 1
call_irrelevant_method()
b = a * 2 # 2
other_method()
c = a - b # 3
```

1. Variable `a` is assigned with a value of `1`.
2. Variable `b` equals to the value of `a` multiplied by `2`.
3. Variable `c` equals to `a` minus `b`.

## Collaborating With Your Editor

The *editor* is your friend and colleague. He will help you to write the best article in the world. However, the editor needs some help from your side as well. Keep in mind the following simple rules:

### Pitching and Outline

* :microphone: When pitching the article, clearly explain what it is going to cover (what language/technologies you are going to use and what skills the readers will gain).
* If you have multiple ideas in mind, pitch them separately.
* Provide a small outline of the article. Of course, this outline may be subject to some changes while you write.

### Asking Questions and Getting Help

Do not hesitate to ask the editor for help as he is here to assist you. However, please remember that the editor works with many authors while carrying out other tasks. Therefore, before asking for help do try to solve the problem by yourself.

### Deadlines

We are quite flexible with the deadlines, but once you have agreed a publication date, please try to prepare the text in time. If you have any problems and will not be able to finish the post in time, please notify the editor.

### Reviewing

After the article is finalized and proofread from your side, send it for review. The editor may request changes or provide some suggestions in order to ensure all articles meet a certain level of quality. The editor's job is not to mock or criticize you but to help you deliver quality content. If you do not agree with the editor, ask for clarifications and clearly state your point of view.

## Writing Your Article

### Creating a New Article

The articles are written in our WordPress CMS. You will be provided with all the necessary login information by your editor.

After logging in, click *Posts* > *Add New* in the main menu:

![](new_post.png)

Next, give your post a title and proceed to writing. :star2:

**Note that the article has to be saved as a draft!**

### Markdown

If you prefer to write in Markdown format using your favourite editor — that's okay as well. Once your article is finished, log into our WordPress and import Markdown file using the Markdown plugin as [instructed in this small video](https://www.youtube.com/watch?v=3EhQ4Xjzg6s).

*Do not send plain Markdown files to your editor — import them into WordPress!*

### Readability

Our WordPress has a special plugin installed that will give you some tips regarding article readability. It can be found right under the text editor:

![](readability.png)

Try to follow the given tips. Of course, it is not mandatory to 100% fulfill all recommendations but some of them are quite important (they were already mentioned above):

* Do not use overly complex words and phrases.
* Do not use too many passive voice.
* Try to use transition words.
* Divide text into sections and subsections.
* Do not write too long paragraphs.

### SEO

SEO is very important for our blog as well. There's a special plugin that gives basic SEO recommendations. It can be found under the text editor:

![](seo.png)

Provide focus keyphrase (which should be discussed with the editor) and observe the results. Try to follow the given tips!
