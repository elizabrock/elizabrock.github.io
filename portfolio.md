---
layout: page
title: Portfolio & Resume
hide-title: true
order: 3
permalink: /portfolio_and_resume
---

# What Have I Done? / Portfolio & Resume

## Summary / What I Bring To The Table

* 12+ years of professional software development
* 10+ years of Ruby/Rails, TDD, web application development
* 4 years of running a Rails consultancy, with my own team of developers
* 3 years of teaching, with 200+ students that have gone on to careers that far exceeded my hopes
* 3 years of managing teams of developers in a more corporate environment
* a strong passion for disciplined software development as both an individual contributor and a leader

## Resume
<!-- TOOD: Link to "detailed resume" -->



## Past Clients & Selected Case Studies

Eliza Brock Software performed software development and other technical services for many clients.  The following are a selection of case studies from the client work that I did there.

<ul>
  {% for case_study in site.case_studies %}
    <li>
      <a href="{{ case_study.url }}">
        <figure>
          <img src="/images/portfolio/logos/{{ case_study.logo }}" alt="{{ case_study.client_name }} Logo" />
          <figcaption>{{ case_study.client_name }}</figcaption>
        </figure>
      </a>
    </li>
  {% endfor %}
</ul>

### Additional Clients

I'm proud of them, but I haven't taken the time to write even a basic summary of my work with these clients:

<ul>
  {% for client in site.data.additional_clients_list %}
    <li>
        <figure>
          <img src="/images/portfolio/logos/{{ client.logo }}" alt="{{ client.name }} Logo" />
          <figcaption>{{ client.name }}</figcaption>
        </figure>
    </li>
  {% endfor %}
</ul>

## References

### What My Clients Say:


<blockquote>
  <p>&#147;Eliza Brock Software was instrumental in helping to extend our products to mid market customers. She and her team are knowledgable, hard working, and well organized. At times we put extraordinary pressure on her team to meet fairly unreasonable deadlines, and each time they buckled down and came through for us. Eliza’s approach to project management, software architecture, and user behavior driven development result in best-of-breed web applications.&#148;</p>
  <cite>&mdash; Rick Thomas, iGoDigital (now Salesforce)</cite>
</blockquote>
<blockquote>
  <p>&#147;We have had the pleasure of working with Eliza on a number of client projects. Each time we work with Eliza she proves herself able to integrate seamlessly as an asset to the team. It is always a pleasure to work with her.&#148;</p>
  <cite>&mdash; Adam Lowe, Hashrocket</cite>
</blockquote>
<blockquote>
  <p>&#147;We hired Eliza Brock Software to conduct a technical interview for our software development company in April 2012. After an initial call to gather requirements for the kind of candidate we were seeking, Eliza completed the technical portion of the interview with our applicant in a professional and timely manner. Her process of quickly identifying the strengths and weaknesses of the applicant has been invaluable to our Company, and lead us to hiring a great team member. I’d recommend Eliza’s services to any company looking to complete a professional and thorough technical interview.&#148;</p>
  <cite>&mdash; Alexander Last, SportsHedge</cite>
</blockquote>
<blockquote>
  <p>&#147;In my entrepreneurial software ventures I often have a need to hire a developer but don’t have the technical knowledge to assess whether the person is capable of the technical requirements of the position. On several occasions I have hired Eliza to conduct technical interviews for my businesses. Her interview services have been highly professional, and her objective assessments have been extremely valuable to me and my businesses in making hiring decisions.&#148;</p>
  <cite>&mdash; David Castor, Alerding Castor Hewitt LLP</cite>
</blockquote>
<blockquote>
  <p>&#147;Eliza Brock Software is quickly becoming our go-to programmer for Sitemason development. It’s the perfect complement to the design side of our partnerships for the Sitemason CMS platform. When HTML/CSS needs to be programmed as a PHP template for our CMS, there is no one better to do the job quickly and completely. The added benefit of having Eliza Brock Software is Eliza’s thorough understanding of the Sitemason CMS and the best uses of the CMS tools. She can help the stakeholders in a development project understand the most effective approach for optimal results.&#148;</p>
  <cite>&mdash; Thomas Conner, Sitemason</cite>
</blockquote>
<blockquote>
  <p>&#147;Eliza is a talented developer and trained on the best practices in the web development world. She can probably get as much done for you as 3 developers could working together. I briefly worked with Eliza on the same project, and know her from the Nashville Ruby community.&#148;</p>
  <cite>&mdash; Josh Crews, Ruby on Rails Developer</cite>
</blockquote>
<blockquote>
  <p>&#147;Eliza was the primary developer for internal/operational web projects during her time at Metova. She took our payment services from a concept to a production system, maintaining development while taking on the role of production support. She tackled a Sisyphean list of priorities and expectations, and came out with a system which met customer expectations and greatly increased the value of Metova’s offerings as a professional services company. She provided a fresh perspective on new technology issues we encountered, and worked diligently to overcome any obstacles.&#148;</p>
  <cite>&mdash; Dave Lane, Metova</cite>
</blockquote>
<blockquote>
  <p>&#147;Eliza’s enthusiasm and deep product skills constantly provide solid feedback into new directions your product can take on. She consistently helps to further new ideas by challenging and improving them. Her communication skills and ability to think quickly on her feet are also major assets that would further any product development team she works for post graduation.&#148;</p>
  <cite>&mdash; Gerald Linn, IBM</cite>
</blockquote>

### What My Students Say:

<blockquote>
  <p>&#147;Eliza’s teachings are the sole reason that I feel confident in my ability to not only work in Ruby on Rails, but to also help teach it to others.&#148;</p>
  <cite>&mdash; Brandon Lyons, Junior Developer at The Skillery</cite>
</blockquote>
<blockquote>
  <p>&#147;During my time at Nashville Software School, Eliza provided high quality technical instruction as well as helpful insights into preparation for entry into entry level developer positions. Her adherence to best practices and encouragement of independent learning were invaluable.&#148;</p>
  <cite>&mdash; Ryan Moret, Quality Assurance Analyst at Change Healthcare</cite>
</blockquote>
<blockquote>
  <p>&#147;Eliza masterfully communicated her wealth of knowledge in a way that allowed people with no previous experience to understand and digest the information.&#148;</p>
  <cite>&mdash; Marcus Fulbright, Junior Back-End Developer at iostudio</cite>
</blockquote>
<blockquote>
  <p>&#147;I had a time-sensitive Ruby on Rails project to support and though I am a seasoned developer, I had no prior experience with Ruby on Rails. I hired Eliza to bring me up-to-speed quickly. She tutored me over the course of 2-3 weeks for a total of about 20 hours and I was off and running. She is knowledgeable, professional, punctual, and communicates well. I highly recommend her design/development/tutorial services and would be happy to serve as a reference.&#148;</p>
  <cite>&mdash; Hollie Brogunier</cite>
</blockquote>
