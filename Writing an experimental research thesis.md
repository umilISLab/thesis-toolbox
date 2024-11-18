# Writing an experimental/research thesis

by Elisabetta Rocchetti (elisabetta.rocchetti@unimi.it)

This guide provides a series of practical hints and tips on how to approach writing a thesis, from reviewing the literature to discussing the results. Designed for thesis writers, the guide covers the different sections that make up a research paper, outlining best practices for each stage and offering concrete suggestions for improving the clarity, structure, and overall quality of the text.

Each section includes methodological tips and stylistic suggestions to help the reader present his or her work effectively. The guide is designed to be consulted both at the dissertation design stage, to plan the work, and during the actual writing process, to assist in the writing and revision process.

# 🔍 Introduction

The purpose of this section is to convince the reader of the importance and interest of the topic addressed in the thesis. To do this, it is essential to present the general context (*background*) of the topic addressed. In particular, you should answer questions such as:

- **Origin of the problem**: What is the context in which the thesis topic arises? How does this context affect the scientific community or society at large?
- **State of the art**: Has your research question already been addressed in the literature?
    - If so, provide a brief summary of the relevant literature. This summary should be both a general introduction and a "thread" connecting the original context to the development of research on your specific question. The goal is to create a chronological and logical narrative that leads from the general context to the specific research question, rather than a list of articles.
    - If not, still follow this structure, but put more emphasis on the reasons why your research is interesting and relevant. In this case, it is important to clearly explain the logical steps that led to the formulation of the research question.
- **Research contribution**: How does your approach differ from previous work? If you are inspired by previous work, what are you trying to improve or extend? It is helpful to briefly introduce the methodology, techniques, or data that make your approach unique from previous studies.
- **Key Findings**: What are the key findings that your approach has enabled you to achieve?
- **Reading path**: What should the reader expect? Provide an overview of the organization of the thesis, indicating what will be covered in subsequent chapters, and pointing out any appendices or additional materials. If available, include a reference to the repository where the code is located.

## 💡 Tips

❓ **But if I write everything in the introduction, what will I write in the rest of the paper?**

Remember that where you are describing what you are going to say in other chapters, you are not replacing the content, but providing a summary of the main points.

❓**I have written a rather long introduction (>2 pages or so). Can I break it down into subsections to make it more organized?**

Subsections are not required, but if you wish to do so, here are some suggestions:

- Subsection titles should answer questions the reader might ask and then reflect on the answer contained in that subsection. **They should not simply state the content. The only exception is for subsections in the References chapter.
- Usually, the only subsection in the introduction that stands out from the rest is the one that describes the structure of the thesis (see the last point above). This is also true for shorter introductions.

❓**In what order should I write the chapters?**

Start with the body of the paper: literature, methodology, experimental results. Then move on to the introduction and conclusion (and abstract, if you want). You don't want anything in the introduction at the end of the thesis that doesn't reflect the work done in the following chapters. Also, you can start writing the thesis while you are doing the experimental analysis; the advice is to start writing the literature section *while* you are reading it.

## ⚠️ Frequent mistakes

- **Not sketching a preliminary table of contents**: when you write a text that must follow a logical flow, it is advisable to start with a bulleted list of the topics to be covered in the order in which you want to present them to the reader. When the table of contents is convincing, you can proceed to write the information in the order you have established. As you write, you may realize that you need more sections or a more detailed breakdown. In that case, you can always update the outline: if you have followed the advice above, your writing will be modular and you can easily move sections around, editing only the sentences that connect the different speeches.
- **Not re-read the table of contents at the beginning of the thesis (*table of contents*)**: the table of contents should be a useful resource for the reader (and for you) to have a mental map of the work. A reader should be able to open your thesis, flip through the table of contents, and quickly find the section of interest. This is why it is helpful to reread the table of contents from time to time: if there is some passage from one title to another that you cannot logically explain, it could mean that the title you chose is not appropriate or that the order of information could be improved.
- **Start introducing acronyms without explaining them**: the first time you use an acronym, you should state its full meaning. For example: Comma-Separated Values (CSV).
- **Introducing technical terms or an inconsistent personal glossary**: when you choose a term to refer to a certain entity, it is important to always use it in the same way. This glossary should be clear and, in the case of technical terms, precise. For example, do not use “training” to refer to the “fine-tuning” of a model.
- **Giving opinions or assertions without citing the source**: scientific writing does not tolerate unsupported statements. For example, we cannot write “It is known that artificial intelligence models perform well on this classification task”: it is known by whom? Who has stated that? Is it a fact that I want to prove with the results of my thesis? If so, I could rephrase it to “As I will demonstrate in later chapters of this thesis, it is known that models...”. It is common, especially in the introduction, to feel tempted to use such phrases; just do a quick search of the articles you have read and their references, or on Google Scholar, to find work that supports what you claim.

# 📚 Literature/Related works

In this section, the reader can expect to find everything needed to fully understand the following chapters. There are two main types of literature works you should consider:

- **Background literature**. This type of material includes established theoretical foundations. Here you will include readings such as books and reference articles, which are widely cited. This section should be introduced first.
- **Related works**. The *related works* concern studies that have addressed problems similar to yours. In this part, you will show previous approaches and how your contribution differs. These papers serve as inspiration for your solution and should be related to the theoretical concepts outlined in the previous section.

For example, imagine a thesis on the use of neural networks for emotion recognition in images.

- Background literature: you could include articles on convolutional neural networks (CNNs), explaining how they work and why they are suitable for image processing. You could also cover emotion recognition, providing an overview of common methods.
- Related works: here you would include studies that use CNNs for emotion recognition, comparing different algorithms and architectures to improve accuracy. You might also discuss works that combine CNNs with other techniques, such as face point detection or visual context analysis.

This section reviews in detail the papers mentioned in the introduction and others that you have found useful to complete the summary. Since you will write this section first, you can make an effective summary from it to use as a skeleton for the introduction.

## 💡Tips

Writing this section may seem tedious, as it is very “compilative.” I recommend that you jot down a few lines immediately after reading an article. This way, you will avoid having to re-read it several times to figure out what information is relevant, and your work will already be largely done.

Categorizing what you read is not easy, but it is essential for breaking the chapter down into thematic subsections and for writing connecting sentences between summaries.

Tag articles immediately after reading to make your job easier later. Categories should be relevant to your topic and needs; pre-existing ones may not always be useful.

I have also written a couple of lines on how to approach literature work. Feel free to ask for guidance on how to read an article!

# ⚙️ Methodology

In this chapter you will finally begin to describe your product. How did you solve the problem you set for yourself?

💡 **Tip**: If you have kept an updated presentation for your supervisors while working on the thesis, you will already have a useful outline for this section.

## ☑️ Structuring

It is very helpful to have an outline describing the step-by-step procedure to be followed. This will not only make it easier for you to write the chapter, but it will also make it easier for the reader to understand the methodology. Here are some suggestions:

- **Design a figure with arrows and blocks to represent the process from initial input to final output.** Many scientific articles use such diagrams in their visual abstract. If you want examples, you can search for articles that feature these diagrams.
- **Drawing the diagram as you write your thesis may be too late.** You may realize that you are not clear on all the steps you have followed. It is common to try different strategies with each choice and to opt for the one that is most convincing.Therefore, keep track of all your decisions and the rationale behind each choice. These notes will become an integral part of your thesis.
- Don't be afraid to admit if a choice was influenced by external factors, such as computational limitations. Transparency rewards in research; it is better to acknowledge difficulties than to hide them.

## 💡 Tips

When you use a technical term or theoretical concept in your methodology, make sure you have already covered it in the *related works* chapter. If necessary, revise that section to add what you need while maintaining consistency with what you have already written.

**Avoid explaining theories in this section!** The methodology should flow without interruption. You can make a brief reference (in 5-6 words) to what you are mentioning, pointing to the relevant chapter of *related works*, to allow the interested reader to elaborate.

Don't be afraid to be schematic: you will have time to use a more discursive style when you comment on the results and write conclusions. In this chapter, you will explain the **what** (e.g. What model did you choose?), the **how** (e.g. How do you want to use the model?) and the **why** (e.g. Why did you choose this model and not others? What results do you expect to achieve?).

Think of this chapter as a cake recipe:

1. Ingredients: what data do you need?
2. Preparation: how did you put everything together?
3. Cooking control: what are your expectations, that is, your hypotheses?

Specifying your expectations allows you to compare your hypotheses with your results in the analysis section. When you write the methodology, try to formulate your hypotheses before you start implementing it in the experiments. Keeping your presentation up to date for supervisors will help you record your hypotheses and avoid creating misleading ones, especially if you have already implemented the methodology and thus already have an idea of the results.

The final description of the “pie” will be in the next chapter, devoted to analyzing the results.

# 📊 Evaluation and analysis of results

In this chapter you will present all the results obtained from the procedures described in the methodology chapter on how to check that the pie is ready. Ideally, the structure of this chapter follows a step-by-step approach, reflecting the problem-solving procedure. For each step in the procedure, the reader can expect to find:

1. **Tools used**: libraries, external tools and resources used to execute the step.
2. **Validation technique**: a brief summary of the technique used to validate the step.
3. **Validation results**: the results obtained, which in the best case scenario include feedback regarding the assumptions made earlier.
4. **Additional analyses**: if necessary, additional analyses to support the validation of the step.

The goal of this chapter is to provide the reader with a clear understanding of the effectiveness of your proposal.

After describing the effectiveness of the steps in your method, it is important to lay out the results of your experiment (key findings). This discussion should be at the end of the chapter, since the last evaluation refers to the last step of your methodology, that is, the one that analyzes the results produced.

In this part, take up the hypotheses made earlier and discuss whether or not they were confirmed. If you do not have a justification for the results obtained, leave the reader some food for thought on possible reasons regarding the correspondence (or not) between the hypotheses and the results. Remember that what has not been proven cannot be presented as a certainty. Use more cautious expressions, such as “In my opinion...” or “The most informed opinion I can give is...”.

Finally, if you have previously divided hypotheses or research questions into sub-hypotheses or specific questions, consider organizing your analysis into subsections.

## ⚠️ Frequent errors

Listed below are some frequent mistakes that can be made in this section:

- **Lack of interpretation**: be sure to provide a clear interpretation of your proposed analysis. For example, the reader may not know that a higher F1-score is better than a lower one.
- **Unintuitive charts**: avoid confusing tables or graphs. They should not take up entire pages (move them to the appendix if necessary). Use inclusive colors that are easy to read, even for those who are color blind.
- **Missing description of tables and figures**: each table and figure should be understandable even without the context of the text. Write clear descriptions for each graphic material; this will also help you prepare content for your final presentation.
- **Unmentioned tables or figures**: do not include tables and figures that you do not discuss in the main text. If you don't mention them it means you don't need them, they just take up space and the reader may ignore them.
- **Use adjectives and comparisons without terms of reference**: to ensure clarity and scientific rigor, avoid adjectives such as “this model is perfect for this task” or comparisons such as “this model is better” without specifying the reference metric and term of comparison.

# 📝 Conclusions and limitations

This section resembles the introduction: it captures the motivation for the work and its development. If the goal of your thesis is not to reproduce third-party methodologies or compare your results with those already obtained, there is no need to mention the literature.

Resume the methodology and analysis of the results, following the same order of presentation you used previously. Include both a summary of the analysis and a discussion of the limitations found: what could be improved? What weaknesses were not resolved?

**Future developments.** This chapter can lay the groundwork for a possible subsection devoted to future developments (*future works*). Here you can propose ways to address the identified limitations, or suggest experiments, validations, or future applications that could start from your thesis work.

If you struggle with your writing, return to the motivations discussed in the introduction chapter and try to imagine how your work fits into the problem scenario described.

**Final reflections.** During the development of the methodology (if the process has been well annotated), questions may have arisen for you that are not directly relevant to the initial research question or ideas that were not explored due to lack of time. This is your opportunity to express and describe these ideas. Do not be afraid to be superficial at this stage; let the reader fill in any blanks.

In an ideal world, the reader, now well-informed and interested in your work, might contact you for coffee and exchange new ideas, inspired by your final “brainstorming.”

# 📑 References and bibliography

If you use LaTeX with Overleaf, you can manage the bibliography by creating a separate BibTeX file (.bib) where you collect all references. In the main file in LaTeX you will then decide which bibliography style to apply, selecting the citation format best suited to your field (e.g., IEEE, APA, or other).

An important aspect is to make sure that the fields for each reference in the BibTeX file are filled in correctly. Usually, you can copy the references directly from the site of the publisher who published the article; in this case, the data should already be formatted correctly. If you are citing an article found on arXiv, check that there is no later official version published in a journal or conference proceedings, as these versions are generally preferred in citations.

In case you are using Word, use LateX with Overleaf.

## Bibliography formatting
Check that the fields extracted from BibTeX produce a result similar to that shown below. If they do not, you may be missing some of them, in which case you need to correct or supplement the citation.

Here are some examples of how references should appear in the compiled bibliography. In addition, [this](https://www.scribbr.com/citing-sources/cite-a-website/) site contains useful examples differentiated according to the citation style adopted.

### Articles in conference proceedings
- Format: Author, A. A., & Author, B. B. (Year). Article Title. In Volume Title (pp. pages). Publisher. DOI or URL (if available)

- Example: Rossi, M., & Bianchi, G. (2023). Intelligent systems for AI literacy. In Proceedings of the European Conference on AI Education (pp. 45-50). Springer. https://doi.org/10.1007/example

### Articles in journals
- Format: Author, A. A., & Author, B. B. (Year). Title of article. Name of the journal, volume(number), pages. DOI

- Example: Rossi, M., & Bianchi, G. (2023). AI literacy in schools. Journal of AI Education, 12(3), 123-130. https://doi.org/10.1234/jai.2023.56789

### Books
- Format: Author, A. A., & Author, B. B. (Year). Book title. Publisher. DOI or URL (if available)

- Example: Rossi, M., & Bianchi, G. (2023). Foundations of AI Literacy. Cambridge University Press. https://doi.org/10.1017/example

### Online resources
- Format: Primary contributors. Title Container title, URL. Accessed Date accessed.

- Example: Slat, Boyan. “Whales Likely Impacted by Great Pacific Garbage Patch.” The Ocean Cleanup, www.theoceancleanup.com/updates/whales-likely-impacted-by-great-pacific-garbage-patch. Accessed Nov. 18, 2024.


# 🤖 Using generative AI to support thesis writing

I have nothing against using generative AI (genAI) for thesis writing. This tool can be particularly useful, especially if you do not have native fluency in the language in which you are writing. Revision using genAI tools can improve the clarity and comprehensibility of the text. Below you will find some tips on how to effectively adopt these tools.

## 💡 Tips

1. **Don't use AI to write for you**: it is essential to have an initial draft written by you. GenAI tools should be used to revise and improve that draft, not to replace it. Remember that generative AI relies on language models and does not always produce reliable information. Even if you are using versions with Internet access, limit information retrieval and focus on revising the writing.
2. **Content Knowledge**: You should already have studied and understood all the information you are including in the thesis. If you are unsure about a topic, consult relevant literature and teaching materials. If you have already developed the methodology without a solid understanding of the content, structural problems and gaps in your work may emerge.
3. **Check the reading flow**: It is important to check that the sections of your work are well connected. Often, when producing texts with generative AI, there is a tendency to require rewriting them section by section. In this way, the various sections are then disconnected and the transition from one concept to the next is not very smooth; in addition, the genAI tool does not always remember that you have already introduced an acronym, so the copied sections may contain repetitive explanations of concepts and acronyms. Rereading the entire work is a crucial step, whether you use genAI tools or not.
4. **Maintain your own writing style**: outputs from genAI tools tend to be homogenized and may not reflect your personal style. Integrate the clarity of generated prompts with your own writing style. Sometimes, it may be helpful to rework an AI suggestion and use only specific parts or words that best suit the way you express yourself.
5. **Check the formatting of the output**: Also pay attention to reformatting the output of genAI tools. I, too, used these tools to improve the readability of this document, but I was careful to check whether the bulleted-list formatting style fit with the context discussed: sometimes I kept it, sometimes I eliminated it. Also, these tools tend to produce titles or sentence highlights with camel notation (first letter of each word capitalized): I personally do not like this style in theses, as it reminds me more of what online content creators adopt to attract the visitor's attention (this is not our goal).
