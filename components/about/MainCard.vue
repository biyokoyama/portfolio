<template>
  <section class="card">
    <div class="card-content">
      <div class="media">
        <div class="media-left">
          <div class="image is-64x64">
            <Logo />
          </div>
        </div>
        <div class="media-content">
          <h2 class="title">
            biyokoyama
          </h2>
          <p>
            <a
              href="https://github.com/biyokoyama/"
              target="_blank"
              rel="noopener"
              class="button is-small"
            >
              <span class="icon">
                <i class="fab fa-github" />
              </span>
              <span>
                Github
              </span>
            </a>
            <a
              href="https://biyokoyama.hatenablog.com/"
              target="_blank"
              rel="noopener"
              class="button is-small"
            >
              <img
                src="@/assets/img/hatenablog.png"
                width="80"
              >
            </a>
          </p>
        </div>
      </div>
      <div class="content">
        <p>
          1992年10月6日生<br>
          石川→北海道→石川→東京
        </p>
        <p>
          電子工作→マイコン→プログラミングという興味を経て、Web開発職に就く。<br>
          バックエンド開発が多い。<br>
          2020年5月現在で5年目。
        </p>
        <p>
          Ruby, JavaScript, PHP, Java<br>
          Ruby on Rails, Vue.js<br>
          AWS (VPC, EC2, CodeDeploy, RDS, S3, ElastiCache, ELB, Route53, CloudFront, SES, SQS, SNS, Lambda, CloudWatch, CloudFormation, IAM)
        </p>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
