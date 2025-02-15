---
title: Downloading your organization's SAML single sign-on recovery codes
intro: 'Organization administrators should download their organization''s SAML single sign-on recovery codes to ensure that they can access {% data variables.product.product_name %} even if the identity provider for the organization is unavailable.'
redirect_from:
  - /articles/downloading-your-organization-s-saml-single-sign-on-recovery-codes
  - /articles/downloading-your-organizations-saml-single-sign-on-recovery-codes
  - /github/setting-up-and-managing-organizations-and-teams/downloading-your-organizations-saml-single-sign-on-recovery-codes
versions:
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Download SAML recovery codes
---

Recovery codes should not be shared or distributed. We recommend saving them with a password manager such as [LastPass](https://lastpass.com/) or [1Password](https://1password.com/).

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.security %}
5. Under "SAML single sign-on", in the note about recovery codes, click **Save your recovery codes**.
   ![Screenshot of the "SAML single sign-on" section. A link, labeled "Save your recovery codes," is highlighted with an orange outline.](/assets/images/help/saml/saml_recovery_codes.png)
6. To save your recovery codes, click **Download**, **Print**, or **Copy**.

  {% note %}

  **Note:** Your recovery codes will help get you back into {% data variables.product.product_name %} if your IdP is unavailable. If you generate new recovery codes the recovery codes displayed on the "Single sign-on recovery codes" page are automatically updated.

  {% endnote %}

7. Once you use a recovery code to regain access to {% data variables.product.product_name %}, it cannot be reused. Access to {% data variables.product.product_name %} will only be available for 24 hours before you'll be asked to sign in using single sign-on.

## Further reading

- "[About identity and access management with SAML single sign-on](/articles/about-identity-and-access-management-with-saml-single-sign-on)"
- "[Accessing your organization if your identity provider is unavailable](/articles/accessing-your-organization-if-your-identity-provider-is-unavailable)"
