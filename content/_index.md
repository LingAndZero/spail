---
title: 

type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <h1 style='text-align: center; font-size: 45px; font-weight: bold;'>
          ABOUT SPAIL 
        </h1>
        The team is comprised of researchers spanning the fields of software engineering and system performance, including research experience in the top institutes and extensive industry experience in both software and hardware technologies with international high-tech companies. The team is fluent in both English and Chinese communications.

        Our team maintains close collaborations with multiple enterprises, research institutions, and overseas universities. With abundant research funding and a vibrant scientific atmosphere, our team provides numerous opportunities for students to participate in a wide array of research and engineering projects. This enables them to showcase their individual capabilities, pursue academic aspirations, and enhance their engineering expertise, fostering both academic growth and engineering proficiency.

        SPAIL has solid projects spanning from the academia to the industry. SPAIL has healthy funding to continue the current projects in computer system performance optimization and explore new ones. Currently, SPAIL is engaged in collaborative projects with several high-tech companies, focusing on performance data collection, analysis, modeling, and prediction across different instruction sets and CPU microarchitectures. The projects aims to enhance the understanding of performance metrics and optimize system efficiency through advanced data analytics and modeling techniques.

        We welcome the following students to join us:
        - 诚实、有激情、有好奇心，追求真实的可复现的工作
        - 追求体系结构和性能分析方向的研究和工程实践
        - Read and write in English
        - 较好的计算机基础知识和一定的动手能力
        - 良好的工程能力，熟悉常用编程语言如Python, C/C++, Rust
        - 良好的数据分析能力, Python packages, Jupyter, Excel, (assisted by ChatGPT, Qwen, etc)

    design:
      css_class: dark
      background:
        color: purple
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: features
    id: research
    content:
      title: "<b>Research Areas</b>"
      items:
        - name: "<b>Software and Hardware Co-Optimization</b>"
          icon: chart-line
          icon_pack: fas
          description: description.
        - name: "<b>Java Language and JDK Optimization</b>"
          icon: java
          icon_pack: fab
          description: description.
        - name: "<b>Cluster Resource Optimization and Performance Optimization</b>"
          icon: bolt
          description: description.
        - name: "<b>AI Computing Acceleration through Software and Hardware Collaboration</b>"
          icon: bolt
          description: description.
        - name: "<b>Online Resource Planning in Distributed Clusters</b>"
          icon: cloud
          icon_pack: fas
          description: description.
        - name: "<b>Sequence Representation Learning and Applications</b>"
          icon: star
          description: description.
    design:
      css_style: "font-size: 20px;"

  - block: contact
    id: contact
    content:
      title: "<b>Contact us</b>"
      email: test@example.org
      phone: XXX XXX XXX XX
      address:
        street: 1689, Jiangnan road 
        city: Ningbo
        postcode: '315048'
        country: China
        country_code: CN
      coordinates:
        latitude: '29.890387'
        longitude: '121.63806'
      directions: E406
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
    design:
      columns: '1'
---
