# Prodigy_GenrativeAI
Hello Everyone! This is my internship task repository where I genrated ai promts and used them in various different aspects of real world applications. I thank prodigy infotech for this Opportunity
Here’s a **more humanized, beginner-friendly, and engaging version of the `README.md`** that still captures the technical essence of your projects:

---

# ✨ AI Projects Showcase — From Text to Art

Welcome! This repository is a personal collection of cool and creative AI projects I’ve worked on — from generating text using GPT-2 to making images with DALL·E Mini, and even training a GAN to create pictures of cars, animals, and more!

Whether you're into **NLP**, **image generation**, or just curious about AI, there's something here for you to explore.

---

## 📂 What's Inside?

### 1️⃣ **Text Generation with GPT-2** — `1.py`

This script uses OpenAI’s GPT-2 model to generate human-like text based on a prompt.

💡 What it does:

* Takes a sentence like *"I enjoy walking with my cute dog"*
* Generates creative continuations using different strategies (like beam search and greedy decoding)

🛠 Tech: Python, PyTorch, HuggingFace Transformers
📦 Install:

```bash
pip install torch transformers
```

▶️ Run:

```bash
python 1.py
```

---

### 2️⃣ **DALL·E Mini Image Generator** — `2.py`

Inspired by OpenAI’s DALL·E, this script turns **text prompts into unique images** — using the Mega model version of DALL·E Mini.

💡 What it does:

* You type a prompt like *"a painting of rolling farmland"*
* It generates beautiful AI artwork!
* Displays multiple results and saves the one you like

🛠 Tech: JAX, Flax, VQGAN, HuggingFace
📦 Install (Recommended to run in Google Colab or a JAX-compatible setup):

```bash
pip install git+https://github.com/robgon-art/dalle-mini.git
pip install git+https://github.com/patil-suraj/vqgan-jax.git
```

---

### 3️⃣ **Text Cleaning + Markov Model Prep (Shakespeare Edition)** — `3.py`

This one dives into classical text processing. It loads plays like *Hamlet*, *Macbeth*, and *Caesar* using the NLTK corpus, cleans them up, and gets them ready for Markov-style text generation.

💡 What it does:

* Cleans old English texts
* Prepares them for cool projects like automatic poetry or Shakespearean chatbots

🛠 Tech: Python, NLTK, spaCy, Markovify
📦 Install:

```bash
pip install nltk spacy markovify
python -m spacy download en
```

▶️ Run:

```bash
python 3.py
```

---

### 4️⃣ **Conditional GAN for CIFAR-10 Image Generation** — `4.py`

This one’s the real deal — a full Conditional GAN built from scratch using TensorFlow. It learns to generate images like dogs, trucks, horses, etc., based on the CIFAR-10 dataset.

💡 What it does:

* Trains a generator and discriminator to create labeled images
* You get custom-generated images with tags like *“Cat”*, *“Frog”*, etc.
* Shows image progress every epoch

🛠 Tech: TensorFlow, Keras, CIFAR-10 dataset
📦 Install:

```bash
pip install tensorflow keras
```

▶️ Run:

```bash
python 4.py
```

---

## 💻 Tools Used

* **Libraries**: Transformers, JAX, TensorFlow, HuggingFace, NLTK, spaCy, Markovify
* **Datasets**: CIFAR-10, Gutenberg Shakespeare Texts

---

## 📘 Notes

* Some scripts (especially the DALL·E one) are best run in **Google Colab** with GPU/TPU enabled.
* Each file is self-contained and doesn't rely on the others.
* Great starting point for AI experiments!

---

## 📜 License & Credit

* DALL·E Mini is shared under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
* Inspired by open-source projects on GitHub & HuggingFace.

---

## 🙌 Let’s Connect!

Have feedback or ideas? Feel free to reach out or suggest improvements!

---

Would you like me to generate this as a downloadable `README.md` file now?
