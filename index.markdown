---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---
<header class="post-header">
    <h1 class="post-title">What makes Kilimnick Pediatrics special?</h1>
</header>


{% capture include_content %}
- We are a warm, friendly, small office, very family oriented.

- We offer same or next day appointments for urgent concerns.

- When calling, you speak directly to someone in the office and not a call-center.

- We are timely in responding to requests for specialist referrals, copies of health records, immunizations, etc.

- We welcome out-of-town college students in need of a local physician to treat chronic medical issues (including prescribing psychiatric and ADHD medications).

- We accept most health insurance plans.

- Patients and parents are all treated with respect and empathy.
{% endcapture %}


{% capture reviews_button %}
    {% include fancy-button.html 
        text='Read reviews'
        href='https://www.google.com/search?client=firefox-b-1-d&q=Joseph+Bernard+Kilimnick%2C+MD#lrd=0x89d6b5a19803a0c5:0x6159c799098020aa,1,,,,'
        new-window='yes'
    %}
{% endcapture %}



{% include column-2h.html 
    left-content=include_content
    right-image='/assets/Joseph-Kilimnick-headshot.png' 
    right-alt='Joseph Kilimnick headshot' 
    right-width='40%'
    right-content='<br>'
    right-suffix=reviews_button
%}

