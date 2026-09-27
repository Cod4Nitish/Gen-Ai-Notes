<div align="center">
  <h1>Generative AI Notes</h1>
  <p>A beginner-friendly study companion for core generative-model concepts</p>
  <img src="https://img.shields.io/badge/status-archived-6B7280?style=flat-square" alt="Status: archived" />
  <img src="https://img.shields.io/badge/topic-Generative%20AI-7C3AED?style=flat-square" alt="Generative AI" />
</div>

> [!NOTE]
> **Archived learning notes.** This beginner-friendly Generative AI reference is retained as a study resource, not as an actively maintained project.

A collection of beginner-friendly notes on Generative AI covering key models like GANs, VAEs, and Transformers.

## Study map

| Area | What to find |
| --- | --- |
| Foundations | A plain-language definition of Generative AI and the kinds of content it can produce. |
| Model families | Introductory references to GANs, VAEs, and Transformers. |
| Learning use | A compact starting point before moving to implementation guides and research papers. |

These notes are intentionally introductory. They are best used as a revision companion, not as production guidance.

## Concept map

~~~mermaid
flowchart LR
    A[Training data or prompt] --> B{Model family}
    B --> C[GAN: generator and discriminator]
    B --> D[VAE: encoder, latent space and decoder]
    B --> E[Transformer: token attention layers]
    C --> F[Generated output]
    D --> F
    E --> F
~~~

## Quick reference

| Topic | Plain-language takeaway | Best next step |
| --- | --- | --- |
| GANs | A generator and discriminator train against one another to create convincing samples. | Read the original GAN paper before implementing one. |
| VAEs | An encoder maps examples into a probabilistic latent space and a decoder reconstructs samples. | Study the reparameterisation idea in the original VAE paper. |
| Transformers | Attention-based layers model relationships between tokens and underpin many modern language models. | Read the original Transformer paper, then build a small attention example. |

### Primary reading

- [Generative Adversarial Nets](https://arxiv.org/abs/1406.2661)
- [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

# Generative AI (Gen AI) - Notes

## 📌 What is Generative AI?

Generative AI is a type of Artificial Intelligence that can create new content such as:

* Text (ChatGPT)
* Images (DALL·E)
* Code (Copilot)
* Audio & Video

Instead of just analyzing data, it generates new data.

---

## 🧠 How Generative AI Works

Generative AI uses Machine Learning models trained on large datasets.

### Common Models:

* GAN (Generative Adversarial Network)
* VAE (Variational Autoencoder)
* Transformers (used in ChatGPT)

---

## ⚙️ Key Concepts

### 1. GAN (Generative Adversarial Network)

* Two networks:

  * Generator → creates fake data
  * Discriminator → checks real or fake
* Both compete with each other

### 2. VAE (Variational Autoencoder)

* Used for generating similar data
* Works using encoding & decoding

### 3. Transformers

* Based on attention mechanism
* Used in NLP tasks
* Example: ChatGPT

---

## 📊 Applications of Generative AI

* Content Creation (blogs, scripts)
* Image Generation
* Chatbots & Virtual Assistants
* Code Generation
* Gaming & Animation

---

## ⚠️ Advantages

* Saves time
* Automates creativity
* Improves productivity

---

## ❌ Limitations

* Can generate incorrect info
* Bias in data
* High computational cost

---

## 🔮 Future Scope

* Personalized AI assistants
* AI-generated movies & games
* Advanced automation in industries

---

## 📌 Conclusion

Generative AI is transforming the way we create content and interact with technology. It has huge potential but must be used responsibly.

