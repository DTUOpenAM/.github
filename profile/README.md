# Open Additive Manufacturing Initiative (Open AM)

<p align="center"><img src="/profile/OpenAMini.png" height="150" alt="Open Additive Initiative logo" /></p>
<h1 align="center">The DTU Open Additive Manufacturing Initiative</h1>

## 🚀 Welcome to the Open AM Initiative!

The **Open Additive Manufacturing Initiative (Open AM)** is an open-source project that aims to fundamentally transform industrial additive manufacturing (AM). Focused specifically on the advanced process of **Laser Powder-bed Fusion (L-PBF)**, and **Vat photopolymerisation (VPP)** Open AM sets out to address the proprietary constraints, high costs, and limited accessibility that currently dominate these fields.

Additive Manufacturing has emerged as a disruptive technology in industries such as aerospace, healthcare, and automotive, enabling unparalleled design freedom, customization, and performance optimization. However, the manufacturing promise of AM is often restricted by the proprietary nature of these industrial systems, which impose limitations on research, innovation, and material exploration. Open AM challenges this by fostering an open-source, community-driven approach to AM technology development.

The industrial Additive Manufacturing (AM) industry is dominated by restrictive business models that significantly limit user control and innovation. Many AM systems are tied to proprietary software requiring costly and recurring license renewals, effectively locking users into ongoing expenses just to operate their machines. Material usage is often restricted through ID-tagging systems, where manufacturers enforce the use of expensive, branded powders, dramatically upmarking costs compared to equivalent open-market materials. Additionally, process parameters—critical for experimentation and optimization—are frequently closed off, preventing users from exploring novel applications or materials. Maintenance contracts add another layer of dependence, as some providers enforce exclusive agreements for servicing, often at steep prices. In extreme cases, ownership of the machine is ambiguous; rather than fully controlling the equipment, users find themselves in arrangements where the solution provider essentially operates the machine on their behalf, right on the factory floor. These practices stifle innovation and make advanced AM technology prohibitively expensive and inaccessible for general purpose manufacturing, for smaller companies, researchers, and innovators. Open AM seeks to dismantle these barriers, building an ecosystem that prioritizes user freedom, transparency, and collaboration.

This initiative is **driven by a mission to democratize access to cutting-edge additive manufacturing technologies**, empowering researchers, educators and industries to engage in innovation without being hindered by high entry costs or restrictive business- and licensing agreements. Open AM embraces principles of **collaboration**, **modularity**, and **transparency**, making it a catalyst for progress in the field of AM.

Hosted by the **Technical University of Denmark (DTU)**, this initiative represents the culmination of **five years of rigorous research, development, and testing**. Funded by the visionary **Poul Due Jensen Foundation**, Open AM is a testament to the transformative potential of open science and engineering. By leveraging an interdisciplinary approach that combines mechanical engineering, materials science, systems design, and software development, Open AM delivers an ecosystem of tools, systems, and knowledge to accelerate the adoption of L-PBF technology.

The Open AM repository is much more than a bundle of files – it is a **your collective for innovation**. It provides everything from hardware blueprints and software suites to firmware solutions and academic insights, all under permissive open-source licenses. This transparency is intended to:
- **Enable exploration**: Researchers and engineers can use Open AM tools to study and develop new processes, materials, and designs.
- **Foster collaboration**: Open AM invites global participation, creating a vibrant community of contributors who can share improvements, ideas, and discoveries.
- **Expand accessibility**: By significantly reducing the cost of entry, Open AM opens the door for smaller organizations, academic institutions, and individuals to access advanced AM technology.

The initiative is built on several pillars:
1. **Hardware**: Modular, cost-efficient, high-performance designs for L-PBF systems and sub-systems.
2. **Software**: Comprehensive control suites and data visualization tools that integrate seamlessly with the hardware.
3. **Documentation**: Meticulously detailed guides for assembly, use, and modification to ensure ease of adoption.
4. **Community**: A global network of developers, researchers, and users collaborating to push the boundaries of AM innovation.

With a focus on **long-term impact**, Open AM not only equips users with the tools to innovate today but also lays the groundwork for a sustainable, community-driven future in additive manufacturing. The initiative bridges the gap between research and application, ensuring that the benefits of advanced manufacturing technology are accessible to all. It serves as a call to action for the AM community to join forces and redefine the future of manufacturing through openness, ingenuity, and collaboration.

---

## 🎯 Purpose and Impetus

The Open AM Initiative was founded to:
- **Break the barriers of proprietary systems**: Open AM challenges the restrictive nature of current L-PBF technologies by providing open-source, modular, and adaptable alternatives.
- **Foster innovation**: Empower researchers, educators, and industries to explore new materials, processes, and design possibilities.
- **Promote accessibility**: Develop cost-efficient, high-performance L-PBF systems that are safe and easy to adopt.

---

## 🛠️ Main Activities

### **1. Development of Open-Architecture L-PBF Systems**
- **Hardware**: Comprehensive blueprints and designs for an open-source, modular L-PBF system.
- **Software**: Open slicers, controllers, and process monitoring tools.
- **Documentation**: Detailed guides for assembly, operation, and modification.

### **2. Research and Academic Contributions**
- Pioneering studies on novel process strategies, materials, and multi-material printing.
- Published papers, conferences, and workshops to share findings with the AM community.

### **3. Collaboration and Community Engagement**
- Creating a thriving open-source community to drive AM technology forward.
- Supporting contributors through resources, forums, and real-time discussions.

---

## 📁 Repository Overview

The Open Additive Manufacturing Initiative GitHub profile is home to a variety of repositories that span hardware, software, and firmware, enabling the modular, open-source nature of the initiative. Below is a categorized list of the repositories and their purposes:

### 🚀 Main Repositories

#### **[OpenLPBF_v2](#)**
- **Description**: The next-generation open-source Laser Powder-bed Fusion (L-PBF) system.
- **License**: CERN Open Hardware Licence Version 2 (Permissive).
- **Purpose**: Central repository for the L-PBF system design files, hardware documentation, and implementation guides.
- **Technologies**: Multi-material printing, modular design, high performance.

#### **[OpenLPBF](#)**
- **Description**: The original L-PBF system that kickstarted the Open AM Initiative.
- **License**: CERN Open Hardware Licence Version 2 (Permissive).
- **Purpose**: Includes design documentation and experimental setups for metal L-PBF.

---

### 🛠️ Sub-System Repositories

#### **[OpenVPP](#)**
- **Description**: A subsystem for open-source variable process parameters.
- **Purpose**: Enables unique control over L-PBF process parameters to optimize builds and experiment with novel scanning strategies.

#### **[OpenVPP_Firmware](#)**
- **Description**: Firmware for the OpenVPP system.
- **Purpose**: Provides embedded software for precise control of process parameters.
- **Technologies**: C++.

#### **[OpenVPP_Software](#)**
- **Description**: Software interface for OpenVPP.
- **Purpose**: Supports intuitive user control and visualization of variable process parameters.
- **Technologies**: HTML, JavaScript.

---

### 🔌 Firmware and Software Repositories

#### **[Open-Controller-Firmware](#)**
- **Description**: The firmware for the unified system controller.
- **License**: MIT License.
- **Purpose**: Ensures precise, real-time coordination of all sub-systems.
- **Technologies**: C.

#### **[OpenAM-SoftwareSuite](#)**
- **Description**: A comprehensive software suite for managing the Open AM system.
- **License**: MIT License.
- **Purpose**: Features process control, job preparation, and data collection tools.
- **Technologies**: HTML, JavaScript.

#### **[G-codePostprocess](#)**
- **Description**: Tools for post-processing and optimizing G-code files for additive manufacturing.
- **License**: MIT License.
- **Purpose**: Improves compatibility and efficiency of G-code for the Open LPBF systems.
- **Technologies**: MATLAB.

---

### 📂 Metadata Repositories

#### **[.github](#)**
- **Description**: Metadata and templates for the Open AM GitHub profile.
- **Purpose**: Hosts configuration files, issue templates, and community guidelines.

---

### 📑 How to Use These Repositories

Each repository contains:
- **Documentation**: Guides and detailed instructions for use.
- **Code**: Open-source software or firmware to download and customize.
- **Issues**: A place to report bugs or request features.
- **Licenses**: Licensing information specific to each repository.

We encourage you to explore these repositories based on your interest and needs. Whether you’re assembling hardware, experimenting with process parameters, or developing new features, there’s something here for everyone!

---

## 🌟 Contribution Guidelines

Want to contribute? Here’s how:
1. **Fork a Repository**: Clone the project you want to contribute to.
2. **Create a Feature Branch**: Work on your proposed changes or enhancements.
3. **Submit a Pull Request**: Open a PR with a clear description of your contribution.
4. **Join Discussions**: Share ideas, feedback, and challenges in the community forums.

---

## 📖 Useful Resources

- [Project Documentation](#)
- [Assembly Guides](#)
- [User Manuals](#)
- [GitHub Basics](https://docs.github.com/en/get-started)

---

## 🤝 Acknowledgments

This initiative would not have been possible without:
- The Poul Due Jensen Foundation for their long-term support and funding.
- The Technical University of Denmark (DTU) for supporting cutting-edge research.
- Our collaborators, contributors, and the AM community for their invaluable input.

---

## 🧙 Fun Facts

- Our modular design can fit through an ordinary industrial door!
- The Open AM system has successfully printed with titanium, aluminum, and even multi-material combinations.
- The initiative has laid the foundation for community-driven L-PBF evolution.

---

## 📬 Contact Us

- **Email**: dbpe@dtu.dk
- **Slack**: [Join Our Community](#)
- **GitHub Discussions**: [Start Here](#)

<p align="center"><img src="/profile/DTU_Logo.png" height="100" alt="DTU logo" /></p>

We believe in open science and collaboration to build a better future for manufacturing. Let’s innovate together!
