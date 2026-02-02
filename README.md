<!-- ===================== TERRAFORM BANNER ===================== -->
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" width="120"/>
</p>

<h1 align="center">🌍 terraform-infra-as-code</h1>

<p align="center">
  <b>Infrastructure Automation • Real Concepts • Visual Learning</b>
</p>

<p align="center">
  👤 <b>Author:</b> <a href="https://www.github.com/arkantandel">Arkan Tandel</a><br/>
  ☁️ Cloud | DevOps | AWS | Terraform
</p>

---

## 🚀 Welcome to the Terraform Master README

Created by **[Arkan Tandel](https://www.github.com/arkantandel)** — this guide helps you understand **Terraform the way professionals think about it**.

Instead of only definitions, this README explains:

- **Why** Terraform is used  
- **How** it works internally  
- **Where** it fits in real DevOps environments  

This is written as if you are **teaching Terraform to someone else**.

---

## 🚀 What is Terraform (In the Real World)?

Terraform is not just a tool — it is the **language of cloud automation**.

In companies, Terraform is used so infra teams don’t manually click on AWS services.  
Instead, they write code that:

- 🏗️ Builds infrastructure  
- 🔄 Updates infrastructure  
- 💣 Destroys infrastructure  
- 🧠 Tracks infrastructure state  
- ☁️ Works across AWS, Azure, and GCP  

Terraform turns infrastructure into **version-controlled software**.

---

## 🧠 How Terraform Actually Works Internally

Terraform follows a **declarative model**.

1. **You write the desired infrastructure** (what you WANT)
2. **Terraform compares it with real cloud state** (what EXISTS)
3. **Terraform creates a plan** showing changes
4. **Terraform applies the plan** and updates the state

👉 This is called **Declarative Infrastructure**, not step-by-step scripting.

---

## 📦 Terraform Project Structure (High-Level Architecture)

```mermaid
graph TD
 A[main.tf] --> B[variables.tf]
 A --> C[providers.tf]
 A --> D[outputs.tf]
 A --> E[modules/]
 E --> F[network module]
 E --> G[compute module]
 E --> H[security module]
