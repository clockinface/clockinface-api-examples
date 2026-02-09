# ClockInFace API Examples

This repository contains **runnable examples and interactive demos** for the
**ClockInFace Facial Recognition Attendance API**.

It is intended for developers who want to **try the API, inspect real requests,
and run end-to-end flows**, not for architectural or conceptual documentation.

> 📘 **Looking for system design or architecture documentation?**  
> Visit the official API documentation site:  
> 👉 [https://clockinface.github.io/clockinface-api-docs/](https://clockinface.github.io/clockinface-api-docs/)

---

## What This Repository Is For

This repository focuses exclusively on **execution-level examples**, including:

- Runnable API usage examples
- End-to-end identity and attendance flows
- Interactive demos using Google Colab
- Reference requests and responses

If you want to understand *how the system works conceptually*, use the
documentation site linked above.  
If you want to **run code**, you are in the right place.

---

## 🚀 Quick Start – Interactive Google Colab Demo

The fastest way to try the ClockInFace API is using the interactive
Google Colab notebook included in this repository.

👉 **Open in Google Colab**  
[https://colab.research.google.com/github/clockinface/clockinface-api-examples/blob/main/clockinface_api_colab_demo.ipynb](https://colab.research.google.com/github/clockinface/clockinface-api-examples/blob/main/clockinface_api_colab_demo.ipynb)

The notebook demonstrates:

- Bearer token authentication
- Registering persons with face images
- Facial recognition for known and unknown identities
- Listing persons and face embeddings
- Attendance-ready identity verification flows

No local setup is required.

---

## 📦 Repository Contents

- `clockinface_api_colab_demo.ipynb`  
  End-to-end Google Colab demo showing how to use the ClockInFace API in a
  realistic attendance workflow.

Additional examples may be added over time as the API evolves.

---

## 🔐 Authentication

All API requests use **Bearer token authentication**.

Authentication tokens are issued per configuration and control:

- Access scope
- Expiration
- Usage limits

A complete authentication example is included in the Colab notebook.

---

## 🔗 Related Resources

- 📘 **API documentation and architecture**  
  [https://clockinface.github.io/clockinface-api-docs/](https://clockinface.github.io/clockinface-api-docs/)

- 🌐 **Official website**  
  [https://clockinface.com](https://clockinface.com)

---

## About This Repository

This repository intentionally avoids:

- System architecture explanations
- Product comparisons
- Marketing content

Its purpose is to provide **clear, working reference implementations** for
developers integrating the ClockInFace facial recognition attendance API.
