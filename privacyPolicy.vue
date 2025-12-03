<script setup lang="ts"></script>

<template>
  <div class="privacy-policy">
    <!-- 标题 -->
    <h1 class="policy-title">寻文明迹App隐私政策</h1>

    <!-- 发布/生效日期 -->
    <div class="policy-date">
      <span>发布日期：2025年11月26日</span>
      <span>生效日期：2025年11月26日</span>
    </div>

    <!-- 引言 -->
    <section class="policy-section">
      <h2 class="section-heading">引言</h2>
      <p class="policy-paragraph">
        欢迎您使用“寻文明迹”App（以下简称“本产品”）。我们深知个人信息对您的重要性，并庄严承诺将按法律法规要求，在安全、可控的前提下保护您的个人信息。本《隐私政策》（以下简称“本政策”）旨在向您清晰地说明，在您使用本产品服务时，我们如何收集、使用、存储、共享和保护您的个人信息，以及您所享有的相关权利。
      </p>
      <p class="policy-paragraph">
        请您在使用本产品前，务必仔细阅读、充分理解本政策（特别是以加粗、下划线等方式提示您的重点内容）及与之相关的《用户协议》。一旦您开始使用本产品，即表示您已同意我们按照本政策处理您的个人信息。如您不同意本政策的任何内容，请您立即停止使用本产品。
      </p>
      <p class="policy-paragraph">
        我们处理的所有个人信息均将进行严格的安全保护。经过去标识化或匿名化处理后的信息，使其无法识别特定个人且不能复原的，不属于个人信息，我们有权在不经您同意的情况下自行使用、共享和公开。
      </p>
    </section>

    <!-- 一、我们如何收集和使用您的个人信息 -->
    <section class="policy-section">
      <h2 class="section-heading">一、我们如何收集和使用您的个人信息</h2>
      <p class="policy-paragraph">
        为实现向您提供核心<strong>AI数字人导览、语音讲解</strong>及个性化等服务的目的，我们会在以下场景中收集和使用您的个人信息，并承诺绝不会收集与提供服务无关的个人信息。
      </p>

      <div class="policy-subsection">
        <h3 class="subsection-heading">1. 账号注册与登录</h3>
        <p class="policy-paragraph">
          当您使用微信授权登录时，我们会收集您的微信唯一标识（OpenID）、头像和昵称，用于快速创建和识别您的账号。
        </p>
        <p class="policy-paragraph">
          为了保障您的账号安全，并实现跨设备数据同步（如游览记录、收藏内容），我们会保存您的登录状态和信息。
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">2. 设备与日志信息</h3>
        <p class="policy-paragraph">
          为优化您的浏览体验，我们会收集您的<strong>设备型号、操作系统版本、唯一设备标识符、屏幕分辨率、语言设置、运营商信息及浏览器类型</strong>。这些信息用于适配展品的最佳展示方式，并进行服务运营支撑和安全保障。
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">3. 位置信息（定位权限）</h3>
        <p class="policy-paragraph">
          在您同意开启位置权限后，我们会收集您的地理位置信息，用于<strong>为您推荐附近的博物馆和景区</strong>。拒绝授权仅会使您无法使用基于位置的推荐服务，但不影响您使用本产品的其他核心功能。
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">4. 相机、相册与麦克风权限</h3>
        <p class="policy-paragraph">
          相机与相册：在您使用拍照识别展品、AI拍照打卡、<strong>AI换脸写真</strong>或更换头像功能时，我们会申请调用您的相机或相册权限。
        </p>
        <p class="policy-paragraph">
          <strong>AI换脸功能特别说明</strong
          >：此功能会通过AI大模型技术，将您实时拍摄的面部或相册中已存的个人照片的面部特征，与我们预设的写真模特面部进行替换，以生成您的个性化AI写真。<strong
            >我们承诺，用于换脸的面部特征数据仅在本次处理中临时使用，不会存储在服务器中或用于其他任何目的。</strong
          >
        </p>
        <p class="policy-paragraph">
          <strong
            >麦克风：在您使用语音导览讲解、发布语音笔记或与社区用户语音互动时，我们会申请调用麦克风权限。若您不授权，将无法使用上述对应的语音相关服务。</strong
          >
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">5. 存储权限</h3>
        <p class="policy-paragraph">
          <strong
            >为保存核销二维码（用于在场馆内兑换导览设备）、您生成的AI写真照片、展品图片及缓存数据，我们需要向您申请存储权限，以确保相关文件能正常写入您的设备。
          </strong>
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">6. 应用列表权限</h3>
        <p class="policy-paragraph">
          为实现向微信等第三方应用分享您的笔记、游览记录或排行榜，我们需要校验您设备上是否安装了相关应用，以确保分享功能的正常使用。
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">7. 支付功能</h3>
        <p class="policy-paragraph">
          当您购买导览服务、套餐包或其他付费产品时，您可以选择微信支付、支付宝或Apple
          Pay等第三方支付服务。支付过程中，我们仅会向支付机构提供<strong
            >订单号及交易金额信息，以确认您的支付指令并完成安全交易。我们不会收集或存储您的银行卡号、支付账户密码等敏感财务信息。
          </strong>
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">8. 客服与售后</h3>
        <p class="policy-paragraph">
          当您联系我们的客服时，<strong
            >为了核验您的身份、查询订单信息以便为您提供帮助，我们可能会使用您的账号信息、注册手机号及相关订单记录。</strong
          >
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">9. 数据融合与统计</h3>
        <p class="policy-paragraph">
          我们可能会将您在不同服务中的信息结合起来（例如，将您的游览轨迹与兴趣标签结合），以便为您提供更个性化、便捷的服务。
        </p>
        <p class="policy-paragraph">
          我们会对用户的使用情况进行统计，形成<strong>无法识别任何特定个人的匿名化统计信息</strong>。此类信息可能被用于分析和优化我们的服务，或与公众及合作伙伴进行共享。
        </p>
      </div>

      <div class="policy-subsection">
        <h3 class="subsection-heading">10. 信息与推送</h3>
        <p class="policy-paragraph">
          我们可能向您发送与服务保障、资讯及市场活动相关的信息，包括但不限于<strong>验证码、服务状态通知、平台资讯、优惠信息等</strong>。您可以根据本政策下文所述路径管理您的推送偏好。
        </p>
      </div>
    </section>

    <!-- 二、征得授权同意的例外 -->
    <section class="policy-section">
      <h2 class="section-heading">二、征得授权同意的例外</h2>
      <p class="policy-paragraph">
        根据相关法律法规，在以下情形中，我们收集、使用您的个人信息无需征得您的授权同意：
      </p>
      <ul class="policy-list">
        <strong><li class="policy-list-item">与我们履行法律法规规定的义务相关的；</li></strong>
        <strong> <li class="policy-list-item">与国家安全、国防安全直接相关的；</li></strong>
        <strong>
          <li class="policy-list-item">与公共安全、公共卫生、重大公共利益直接相关的；</li></strong
        >
        <strong>
          <li class="policy-list-item">与刑事侦查、起诉、审判和判决执行等直接相关的；</li></strong
        >
        <strong>
          <li class="policy-list-item">
            出于维护您或其他个人的生命、财产等重大合法权益但又很难得到本人同意的；
          </li></strong
        >
        <strong>
          <li class="policy-list-item">所收集的个人信息是您自行向社会公众公开的；</li></strong
        >
        <strong>
          <li class="policy-list-item">
            从合法公开披露的信息中收集个人信息的，如合法的新闻报道、政府信息公开等渠道；
          </li></strong
        >
        <strong>
          <li class="policy-list-item">根据与您签订和履行合同所必需的；</li>
        </strong>
        <strong>
          <li class="policy-list-item">
            用于维护所提供的产品或服务的安全稳定运行所必需的，例如发现、处置产品或服务的故障；
          </li></strong
        >
        <strong> <li class="policy-list-item">法律法规规定的其他情形。</li></strong>
      </ul>
    </section>

    <!-- 三、我们如何共享、转让您的个人信息 -->
    <section class="policy-section">
      <h2 class="section-heading">三、我们如何共享、转让您的个人信息</h2>
      <p class="policy-paragraph">
        <strong> 我们绝不会将您的个人信息出售给任何公司、组织或个人 </strong
        >。仅在以下情况下，我们可能会共享您的信息：
      </p>
      <p class="policy-paragraph">
        与授权合作伙伴共享：仅为实现本政策中声明的目的，我们的某些服务将由授权合作伙伴提供。例如，委托第三方进行数据存储与分析、支付处理等。我们会与合作伙伴签署严格的保密协议，要求他们按照我们的指示、本政策以及其他任何相关的保密和安全措施来处理个人信息。
      </p>
      <p class="policy-paragraph">
        在法律要求时：如前述第二条规定的情形，或响应司法或行政机构的合法要求。
      </p>
    </section>

    <!-- 四、我们如何保护您的信息安全 -->
    <section class="policy-section">
      <h2 class="section-heading">四、我们如何保护您的信息安全</h2>
      <p class="policy-paragraph">我们已建立全面的数据安全管理体系，致力于保障您的个人信息安全：</p>
      <ol class="policy-list">
        <li class="policy-list-item">
          我们采用加密技术（如SSL）在数据传输过程中对您的信息进行保护。
        </li>
        <li class="policy-list-item">
          我们设有严格的内部数据安全管理制度和流程，对数据的访问进行严格的权限控制，避免数据被违规使用。
        </li>
        <li class="policy-list-item">我们定期对员工进行信息安全培训，并签署保密协议。</li>
      </ol>
    </section>

    <!-- 五、您的权利 -->
    <section class="policy-section">
      <h2 class="section-heading">五、您的权利</h2>
      <p class="policy-paragraph">您对您的个人信息享有以下权利：</p>
      <p class="policy-paragraph">
        <strong>访问、更正与删除</strong
        >：您可以通过App内“我的”相关功能，访问、更正您的个人资料，或自主删除您的发布内容、游览记录。
      </p>
      <p class="policy-paragraph">
        <strong>改变授权范围</strong
        >：您可以在设备的【设置】中随时关闭相机、定位、麦克风等权限，以改变或撤销您对部分个人信息的授权。
      </p>
      <p class="policy-paragraph">
        <strong>账户注销</strong
        >：您可以通过App内提供的路径申请注销账户。在您主动注销账户后，我们将停止为您提供产品服务，并根据适用法律的要求删除您的个人信息或进行匿名化处理。
      </p>
    </section>

    <!-- 六、本政策的更新 -->
    <section class="policy-section">
      <h2 class="section-heading">六、本政策的更新</h2>
      <p class="policy-paragraph">
        我们的服务和相关技术将随用户需求和技术发展而持续优化，因此我们可能会适时更新本政策。<strong>如有任何变更，我们会在本政策专用发布页面上发布最新版本，并通过显著方式（如在App内通知）提醒您。若您继续使用我们的服务，即表示您同意受修订后的政策约束</strong>。
      </p>
    </section>

    <!-- 七、其他 -->
    <section class="policy-section">
      <h2 class="section-heading">七、其他</h2>
      <p class="policy-paragraph">
        本产品内所有数字人形象、音频、图文内容均为原创，享有完整的知识产权。
      </p>
      <p class="policy-paragraph">本政策与您所使用的《寻文明迹用户协议》是不可分割的整体。</p>
      <p class="policy-paragraph">
        如您对本政策或您的个人信息处理有任何疑问、意见或建议，可通过App内客服渠道与我们联系。
      </p>
      <p class="policy-reminder">
        <strong
          >再次提醒：请您仔细阅读本政策（特别是加粗内容），在确认充分理解并同意全部条款后再开始使用我们的服务。</strong
        >
      </p>
    </section>
  </div>
</template>

<style lang="scss" scoped>
// 基础样式（适配所有设备）
.privacy-policy {
  padding: 1.2rem 0.8rem;
  font-size: 16px;
  letter-spacing: 2px;
  line-height: 1.8;
  color: #333;
  max-width: 100vw;
  overflow-x: hidden;

  // 强制加粗标签生效
  strong {
    font-weight: 700 !important; // 确保所有场景下加粗
    color: #222;
  }

  // 标题
  .policy-title {
    font-size: 20px;
    font-weight: 600;
    text-align: center;
    margin-bottom: 1.2rem;
    letter-spacing: 4px;
  }

  // 日期栏（手机端垂直排列）
  .policy-date {
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
    margin-bottom: 1.5rem;
    text-align: center;
    font-size: 14px;
    color: #666;
  }

  // 章节容器
  .policy-section {
    margin-bottom: 1.5rem;
  }

  // 章节标题（加粗突出）
  .section-heading {
    font-size: 18px;
    font-weight: 700;
    margin: 1.2rem 0;
    letter-spacing: 3px;
    color: #222;
  }

  // 子章节标题
  .subsection-heading {
    font-size: 16px;
    font-weight: 600;
    margin: 0.8rem 0;
    letter-spacing: 2px;
    color: #333;
  }

  // 段落样式
  .policy-paragraph {
    text-indent: 1.5em;
    margin-bottom: 0.8rem;
    word-break: break-all;
  }

  // 列表样式
  .policy-list {
    margin-left: 2em; // 调整数字与文本的间距（手机端适配）
    margin-bottom: 0.8rem;
    list-style: decimal; // 关键：显示阿拉伯数字（1、2、3...）
    padding-left: 0; // 清除默认内边距，避免缩进过大
  }

  .policy-list-item {
    margin-bottom: 0.5rem;
    word-break: break-all;
  }

  // 提醒文本
  .policy-reminder {
    font-weight: 700;
    margin-top: 1.2rem;
    text-indent: 1.5em;
  }

  // 子章节容器
  .policy-subsection {
    margin-bottom: 1rem;
  }
}

// 平板/电脑端适配
@media (min-width: 768px) {
  .privacy-policy {
    padding: 2rem;
    font-size: 22px;
    letter-spacing: 10px;
    line-height: 2;

    .policy-title {
      font-size: 18px;
      letter-spacing: 12px;
      margin-bottom: 1.5rem;
    }

    .policy-date {
      flex-direction: row;
      gap: 3rem;
      font-size: 22px;
      color: #333;
    }

    .section-heading {
      font-size: 22px;
      letter-spacing: 10px;
      margin: 1.5rem 0;
    }

    .subsection-heading {
      font-size: 22px;
      letter-spacing: 10px;
      margin: 1rem 0;
    }

    .policy-paragraph {
      text-indent: 2em;
      margin-bottom: 1rem;
    }

    .policy-list {
      margin-left: 4em;
    }

    .policy-reminder {
      margin-top: 1.5rem;
      text-indent: 2em;
    }
  }
}
</style>
