---
type: PageLayout
title: Manyue Javvadi | AI Innovator & Business Strategist
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/Try.webp
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75

sections:
  - type: HeroSection
    colors: colors-f
    title: Bridging AI and Business
    subtitle: >
      Welcome to the intersection of artificial intelligence and entrepreneurial vision.
    text: >
      I'm Manyue Javvadi, a Machine Learning enthusiast passionate about creating projects that push the limits of innovation. Guided by the belief that 
      "Imagination is more powerful than knowledge," as Albert Einstein once said, I strive to develop solutions that enhance human potential, not replace it. 
      Explore the ideas and creations that aren't just part of the present—they're shaping a future where technology and humanity thrive together.
    actions:
      - type: Button
        label: Explore My Vision
        url: /projects/
        style: primary
      - type: Link
        label: My Journey
        url: /info/
    styles:
      self:
        height: auto
        width: wide
        margin: ["mt-0", "mb-0", "ml-0", "mr-0"]
        padding: ["pt-36", "pb-48", "pl-4", "pr-4"]
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: ["pt-12", "pb-12", "pl-4", "pr-4"]
        justifyContent: center
        borderWidth: 1
        borderStyle: solid

  - type: FeaturedProjectsSection
    colors: colors-f
    title: Innovation Showcase
    subtitle: Where AI Meets Real-World Impact
    projects:
      - type: FeaturedItem
        title: Jamboree Education - Linear Regression
        subtitle: Business Case Study using Linear Regression
        text: >
          It helps in creating new feature where students/learners can come to Jamboree Education and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.
        actions:
          - type: Link
            label: Learn More
            url: /projects/project-three/

      - type: FeaturedItem
        title: LoanTap - Logistic Regression
        subtitle: Business Case Study using Logistic Regression 
        text: >
          LoanTap is a fintech startup that uses AI to predict loan default risk. I have used Logistic Regression model to predict the probability of loan default for borrowers.
          This is a demonstration of the following video:
        actions:
          - type: Link
            label: Explore Project
            url: /projects/healthcare-analytics

      - type: FeaturedItem
        title: Auto Feature Selection tool for Machine Learning Problems.
        subtitle: Developed a tool that automatically selects the best features for a machine learning problem. 
        text: >
          This tool uses a combination of feature selection algorithms and machine learning models to select the best features for a machine learning problem.
          Our solution focuses on:
          • Demand forecasting
          • Inventory management
          • Route optimization
        actions:
          - type: Link
            label: View Details
            url: /projects/supply-chain-ai
    styles:
      self:
        height: auto
        width: wide
        margin: ["mt-0", "mb-0", "ml-0", "mr-0"]
        padding: ["pt-24", "pb-24", "pl-4", "pr-4"]
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    actions:
      - type: Link
        label: View All Projects
        url: /projects

  - type: QuoteSection
    colors: colors-f
    quote: "The future is not something we enter. The future is something we create."
    name: Leonard I. Sweet
    styles:
      self:
        height: auto
        width: wide
        margin: ["mt-0", "mb-0", "ml-0", "mr-0"]
        padding: ["pt-36", "pb-36", "pl-4", "pr-4"]
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center

  - type: CtaSection
    colors: colors-f
    title: View My Resume
    text: Get a comprehensive overview of my skills, experience, and achievements.
    actions:
      - type: Link
        label: Open Resume
        url: https://drive.google.com/file/d/1-Vu7xZMZ90Srz1IXc_WqQR6kOL_bd7mg/preview
        showIcon: true
        icon: arrowRight
        style: primary
        elementId: resume-link
    styles:
      self:
        height: auto
        width: wide
        margin: ["mt-0", "mb-0", "ml-0", "mr-0"]
        padding: ["pt-24", "pb-24", "pl-4", "pr-4"]
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: center

  - type: CtaSection
    colors: colors-f
    title: Revolutionizing Industries with AI
    text: >
      I'm building an NLP-powered startup to transform customer experiences in retail and hospitality. Ready to innovate and create groundbreaking solutions for your industry challenges?
    actions:
      - type: Button
        label: Let's Innovate Together
        url: https://www.linkedin.com/in/manyue-javvadi-datascientist/
        style: primary
      - type: Link
        label: Explore My Code
        url: https://github.com/Manyue-datascientist
    styles:
      self:
        height: auto
        width: wide
        margin: ["mt-0", "mb-0", "ml-0", "mr-0"]
        padding: ["pt-24", "pb-24", "pl-4", "pr-4"]
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: center

---
