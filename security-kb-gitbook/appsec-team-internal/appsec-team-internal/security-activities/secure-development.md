# Secure Development

{% tabs %}
{% tab title="SDARQ" %}
**Description:**

How do we enable developers to understand what security requirements are applicable to a service they are launching as early as possible? How do we make sure security is involved in a discussion ideally at the design/architecture phase?

**Tools:**

* SDARQ: [https://sdarq.dsp-appsec.broadinstitute.org/](https://sdarq.dsp-appsec.broadinstitute.org/)
{% endtab %}

{% tab title="CI/CD security" %}
## CI/CD security

**Description:**

Are our deployments secure with the right levels of authorization and authentication so that only the "right" people can kick off deployments? Production deploys should not be able to run from "random" PRs without some sort of security process.
{% endtab %}

{% tab title="Secrets Management" %}
## Secrets Management

**Description:**

Make sure secrets are properly stored and encrypted. Access to secrets is granted on a need-to-know basis. Secrets must be regularly expired and rotated. Robust logs are stored so that access can be audited in the future.

**Tools:**

* Vault: [https://broadinstitute.atlassian.net/wiki/spaces/DO/pages/113874856/Vault](https://broadinstitute.atlassian.net/wiki/spaces/DO/pages/113874856/Vault)
* Secret Manager
* Git Secrets
{% endtab %}
{% endtabs %}

