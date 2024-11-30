# Ceph-LLM: Unlocking the Power of Community driven and Open Source Ceph LLM model

In the ever-evolving world of artificial intelligence (AI), **Large Language Models (LLMs)** have transformed the way we interact with technology. However, challenges such as data transparency and the lack of community-driven contributions often hinder their development. Enter **Ceph-LLM**, an innovative initiative made possible by Instructlab, an open source finetuning framework created with the collaboration of IBM Research and Red Hat, that seeks to create an open-source, community-driven LLM tailored to the Ceph ecosystem.

* TOC
{:toc}

---

## The Problem with Current LLMs

While LLMs have demonstrated incredible potential, two major concerns persist:

1. **Transparency in Data Training:** Users often lack clarity about the data used to train these models, raising trust and ethical concerns.
2. **Limited Community Contribution:** Most models do not allow external input to refine or expand their training data.

Ceph-LLM addresses these issues head-on with a mission to empower the Ceph community through collaborative and transparent AI solutions.

---

## Mission and Vision of Ceph-LLM

The goal of Ceph-LLM is to:
- Develop and maintain a community-driven, open-source LLM that provides instant insights into Ceph-related topics.
- Create a centralized hub for Ceph knowledge, fostering innovation, and collaboration.

The vision is to become the leading resource for Ceph expertise, enhancing user experience and pushing the boundaries of what the community can achieve together.

---

## How Ceph-LLM Works

Ceph-LLM leverages a robust **technology stack** to streamline model creation and refinement. Here’s a breakdown of the workflow:

### 1. Base Model Selection

Several LLMs serve as the foundation for Ceph-LLM, including:
- **Meta’s Llama**  
- **OpenAI’s GPT Family**  
- **IBM Granite Models** (notable for their ethical and governance focus)

The IBM **Granite-7B-Base model** is often the preferred choice, offering a comparitively small yet with a balance of performance, scalability, and transparency.

### 2. Adding Private or Enterprise Data

The techniques available which integrates enterprise and Ceph(or any context)-specific data are:
- **Retrieval-Augmented Generation (RAG):** For context-rich responses.
- **Fine-Tuning:** Employing methods like PEFT, LoRA, and QLoRA to enhance model specificity.
- **IBM InstructLab:** A cost-effective, open source and collaborative tool for refining LLMs by adding data comprehensively.

### 3. Publishing and Accessibility

The final refined model is published on platforms like Hugging Face, ensuring community access and feedback.

---

## IBM InstructLab: The Backbone of Ceph-LLM

IBM’s **InstructLab** plays a pivotal role in reducing the costs of fine-tuning LLMs by enabling collaborative contributions. Key features include:
- A **taxonomy framework** for structured data addition.
- YAML templates for skills and knowledge contributions.
- A simplified interface for model serving and interaction.

![instructlab workflow](/img/2024-11-30-Ceph-LLM-Open-Source/instructlab_workflow.png)


---

## Ceph-LLM in Action

### For Data Contributors:
- Clone/Fork the Ceph taxonomy from GitHub.
- Add new Q&A entries or attribution files specific to your domain.
- Use Markdown for grounded knowledge contributions.
- Submit pull requests to integrate updates into the model.

### For Model Consumers:
- Access models through **Docker images**, **Hugging Face**, or **Langchain integrations**.
- Deploy models on platforms like **Gradio**, **Streamlit**, or IBM’s **Watsonx**.

### For Infrastructure Management:
- Host models on RHEL AI (Red Hat Enterprise Linux AI) in IBM Cloud.
- Utilize IBM Vela for scalable deployment.

---

## FAQs: Addressing Key Concerns

1. **Why is the output sometimes inaccurate?**  
   Fine-tuning relies on diverse and comprehensive input data. Community contributions play a vital role in improving accuracy.

2. **Why use IBM Granite over other LLMs?**  
   Granite models emphasize ethics and governance, aligning with the project’s transparency goals.

3. **Can RAG and fine-tuning coexist?**  
   Yes! Combining both approaches ensures contextual and accurate responses.

---

## Conclusion: A Community-Driven Future

Ceph-LLM exemplifies the power of open collaboration in AI development. By addressing transparency and enabling contributions, it empowers the global Ceph community to push boundaries, solve challenges, and innovate together.

To get involved, explore Ceph-LLM on [Hugging Face](https://huggingface.co/instructlab) or contribute via GitHub. Together, we can build a smarter, more connected future.

Would you like to contribute or learn more? Let us know in the comments!
