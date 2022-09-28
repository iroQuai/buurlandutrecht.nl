---
layout: contact
title: Contact
lastmod: 2022-09-28T19:19:44.957Z
---
Persoonlijk contact wordt altijd gewaardeerd! Gebruik het formulier hieronder om een berichtje te sturen.

{{< netlify-form name="contact" >}}
  {{< form-input id="firstname" type="text" placeholder="John" label="First Name:" required="true" >}}
  {{< form-input id="lastname" type="text" placeholder="Doe" label="Last Name:" >}}
  {{< form-input id="reply_email" type="email" placeholder="john.doe@email.com" label="Reply-To Email:" required="true" >}}
  {{< mult-input label="Gender:" name="gender" required="true" add_other="true" type="select" >}}
    {{< form-option label="Male" value="male" >}}
    {{< form-option label="Female" value="female" >}}
  {{< /mult-input >}}
  {{< form-input type="text" id="submit_reason" required="true" label="Reason for contacting:" placeholder="Problem with site" >}}
  {{< form-input id="contact_description" type="textarea" label="Explain:" required="true" >}}
{{< /netlify-form >}}

%%% add form via https://slibbe.github.io/docs/pages/netlify-forms/ %%%