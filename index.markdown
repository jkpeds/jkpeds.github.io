---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

{% capture include_content %}
What makes Kilimnick Pediatrics special?

- Warm, friendly, small office field, very family oriented.
- Offers same or next day appointments for urgent concerns.
- When calling, you speak directly to someone in the office and not a call-center.
- Timely in responding to requests for specialist referrals and copies of health records, immunizations, etc..
- Welcomes out-of-town college students in need of a local physician to treat chronic medical issues (including prescribing psychiatric, and ADHD medications).
- Accepts most health insurance plans.
- Patients and parents are all treated with respect and empathy.
{% endcapture %}

{% include column-2h.html 
    right-image='/assets/Joseph-Kilimnick-headshot.png' 
    right-alt='Joseph Kilimnick headshot' 
    left-content=include_content 
%}


{%- endif %}