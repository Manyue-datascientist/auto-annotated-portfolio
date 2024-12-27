---
type: ProjectFeedLayout
title: Projects
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: https://media.giphy.com/media/tnPxFTth7qoDiw1rnm/giphy.gif
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 50
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  projects:  # Changed from 'items'
    - type: FeaturedItem
      title: LoanTap - Logistic Regression
      subtitle: Business Case Study using Logistic Regression
      description: >  # Changed from 'text'
        LoanTap is a fintech startup that uses AI to predict loan default risk. I have used Logistic Regression model to predict the probability of loan default for borrowers.
      featuredImage:
        type: ImageBlock
        url: [your-image-url-here]  # Add an image URL if you have one
        altText: LoanTap Project
      actions:
        - type: Link
          label: Explore Project
          url: https://manyue-portfolio.streamlit.app/
      
  showDate: false
  showDescription: true
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-a
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
---
