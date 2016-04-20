---
process:
  twig: true
---
## Sign up for beta access

Blandit varius ut praesent nascetur eu penatibus nisi risus faucibus nunc.

{{ simple_form({ token: "YYY", template_file: "newsletter", fields: { email: { placeholder: "Email Address" }, submit: { title: "Sign Up" } }, messages: { success: "Your email is registered to our Newsletter, Thanks!!" } }) }}
