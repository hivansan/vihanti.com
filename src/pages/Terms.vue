<template>
  <div>
    <app-header>
      <h1 class="title">Terms of Service</h1>
    </app-header>

    <section class="section is-fullwidth">
      <div class="columns is-centered">
        <div class="column is-8">
          <div class="content">
            <p>
              <em>Last updated: January 29, 2020</em>
            </p>

            <p>
              By using our website ("Service"), you are agreeing to be bound by
              the following terms and conditions ("Terms of Service").
            </p>

            <p>
              Vihanti Digital Services Pvt. Ltd. ("Company") reserves the right
              to update and change these Terms of Service without notice.
            </p>

            <h2>Modifications to the Service and Prices</h2>

            <ol>
              <li>
                The Company reserves the right at any time and from time to
                time to modify or discontinue, temporarily or permanently, any
                part of the Service with or without notice.
              </li>
              <li>
                The Company shall not be liable to you or to any third party
                for any modification, price change, suspension or
                discontinuance of the Service.
              </li>
            </ol>

            <h2>Copyright and Content Ownership</h2>

            <p>
              The look and feel of the Service is copyright&copy; to the
              Company. All rights reserved. You may not duplicate, copy, or
              reuse any portion of the HTML, CSS, JavaScript, or visual design
              elements without express written permission from the Company.
            </p>

            <h2>General Conditions</h2>

            <ol>
              <li>
                Your use of the Service is at your sole risk. The service is
                provided on an "as is" and "as available" basis.
              </li>
              <li>
                You understand that the Company uses third party vendors and
                hosting partners to provide the necessary hardware, software,
                networking, storage, and related technology required to run the
                Service.
              </li>
              <li>You must not modify, adapt or hack the Service.</li>
              <li>
                You must not modify another website so as to falsely imply that
                it is associated with the Service or the Company.
              </li>
              <li>
                You agree not to reproduce, duplicate, copy, sell, resell or
                exploit any portion of the Service, use of the Service, or
                access to the Service without the express written permission by
                the Company.
              </li>
              <li>
                The failure of the Company to exercise or enforce any right or
                provision of the Terms of Service shall not constitute a waiver
                of such right or provision. The Terms of Service constitutes
                the entire agreement between you and the Company and govern
                your use of the Service, superceding any prior agreements
                between you and the Company (including, but not limited to, any
                prior versions of the Terms of Service).
              </li>
              <li>
                Questions about the Terms of Service should be sent to
                <a
                  href="mailto:hello@vihanti.com"
                >hello@vihanti.com</a>.
              </li>
            </ol>

            <p class="is-size-7 is-italic">
              Adapted from the
              <a href="https://github.com/basecamp/policies">Basecamp open-source policies</a>
              /
              <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue'

export default {
  name: "Terms",
  components: {
    AppHeader
  },
  metaInfo: {
    title: "Terms of Service",
    meta: [
      { name: "description", content: "We'd love to talk about how we can help unleash creativity for your business!  Schedule a free discovery call today!" }
    ]
  }
}
</script>