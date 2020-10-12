---
templateKey: blog-post
title: A beautiful spring day
date: 2020-10-11T23:37:37.563Z
description: Once upon a time...
featuredpost: true
featuredimage: https://res.cloudinary.com/sharing-is-the-key/image/upload/v1602455011/sample.jpg
tags:
  - Spring
---
Spring may not be the best loved season, but it’s definitely the most eagerly anticipated. That’s because the first day of spring marks the end of *winter*, which inevitably gets the cold shoulder in seasonal popularity contests. For many, the official end of winter and its chilly weather is something truly worth celebrating.

One way to welcome the arrival of spring is to send a cheerful, sweet, or funny message to your friends. But don’t worry if the right words don’t immediately *spring* to mind. We’ve got a whole list of happy spring wishes to choose from below.

![Happy Spring](https://allwording.com/wp-content/uploads/2020/01/happy-spring-pin-400.png)

```javascript
import React from 'react'
import PropTypes from 'prop-types'
import { graphql } from 'gatsby'
import Layout from '../components/Layout'
import Content, { HTMLContent } from '../components/Content'

export const AboutPageTemplate = ({ title, content, contentComponent }) => {
  const PageContent = contentComponent || Content

  return (
    <section className="section section--gradient">
      <div className="container">
        <div className="columns">
          <div className="column is-10 is-offset-1">
            <div className="section">
              <h2 className="title is-size-3 has-text-weight-bold is-bold-light">
                {title}
              </h2>
              <PageContent className="content" content={content} />
            </div>
          </div>
        </div>
      </div>
    </section>
  )
}

AboutPageTemplate.propTypes = {
  title: PropTypes.string.isRequired,
  content: PropTypes.string,
  contentComponent: PropTypes.func,
}

const AboutPage = ({ data }) => {
  const { markdownRemark: post } = data

  return (
    <Layout>
      <AboutPageTemplate
        contentComponent={HTMLContent}
        title={post.frontmatter.title}
        content={post.html}
      />
    </Layout>
  )
}

AboutPage.propTypes = {
  data: PropTypes.object.isRequired,
}

export default AboutPage

export const aboutPageQuery = graphql`
  query AboutPage($id: String!) {
    markdownRemark(id: { eq: $id }) {
      html
      frontmatter {
        title
      }
    }
  }
`

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### My Great Heading {#custom-id}

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

~~The world is flat.~~ We now know that the world is round.

Gone camping! :tent: Be back soon.

That is so funny! :joy:



