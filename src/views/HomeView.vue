<template>
  <!-- header -->
  <header class="min-vh-100 position-relative">
    <div class="deco-box position-absolute top-0 start-0"></div>
    <div class="deco-box position-absolute bottom-0 end-0"></div>
    <div
      class="position-absolute bg-cover bg-attachment-fixed"
      style="
        top: 30px;
        right: 30px;
        bottom: 30px;
        left: 30px;
        background-image: url(https://images.unsplash.com/photo-1612282130134-49784d98ac61?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2118&q=80);
      "
    ></div>
    <div
      class="position-absolute start-50 top-50 translate-middle text-white text-center"
    >
      <h1 class="display-1 fw-bold">陳 六角</h1>
      <hr class="mb-1 mx-n3" />
      <h2>Hex Chen</h2>
      <p>愛、勇氣與永不放棄的心</p>
    </div>
  </header>
  <!-- 我的冒險故事 -->
  <div class="container py-5">
    <div class="row justify-content-center flex-md-row-reverse gy-3">
      <div class="col-md-4">
        <img
          src="https://images.unsplash.com/photo-1612282131240-6e878907d0f6?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1121&q=80"
          class="w-100 object-fit-cover"
          height="500"
          alt="我的冒險故事圖片"
        />
      </div>
      <div class="col-md-5 d-flex align-items-center">
        <div>
          <h2 class="display-4">我的冒險故事</h2>
          <p>
            伍威爾遜曾經提過，每個人都是他自己個性的工程師。這段話對世界的改變有著深遠的影響。現在，正視十二號混泥土的問題，是非常非常重要的。因為，問題的關鍵究竟為何？
          </p>
          <p>
            需要考慮周詳十二號混泥土的影響及因應對策。其實，若思緒夠清晰，那麼十二號混泥土也就不那麼複雜了。經過上述討論，佩特羅尼烏斯曾提出，光有外表的美是不夠的。言談、智慧、表演、甜蜜的笑語都勝過自然創造的單純的美。一切藝術手段都是美的調料。他會這麼說是有理由的。
          </p>
          <a href="#" class="btn btn-outline-primary w-100 mt-4"
            >看更多關於我的故事</a
          >
        </div>
      </div>
    </div>
  </div>
  <!-- 三欄卡片 -->
  <div class="bg-light py-4 p-md-5 mt-5">
    <div class="container">
      <h2 class="display-4 text-center mb-4">我的實戰作品</h2>
      <div class="row row-cols-1 row-cols-md-3 gy-4">
        <div class="col">
          <div class="card text-white border-5 h-100">
            <img
              src="https://images.unsplash.com/photo-1615976909545-a2d402c7dac3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
              alt=""
              class="card-img h-100 object-fit-cover"
            />
            <div class="card-img-overlay top-auto bg-dark-gradient">
              <h5 class="card-title">小說作品</h5>
              <p class="card-text">
                我們都有個共識，若問題很困難，那就勢必不好解決。經過上述討論，需要考慮周詳小說的影響及因應對策。
              </p>
              <a href="#" class="btn btn-outline-light stretched-link w-100"
                >更多內容</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card text-white border-5 h-100">
            <img
              src="https://images.unsplash.com/photo-1461902144240-fcb450abaa4a?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
              alt=""
              class="card-img h-100 object-fit-cover"
            />
            <div class="card-img-overlay top-auto bg-dark-gradient">
              <h5 class="card-title">設計小物</h5>
              <p class="card-text">
                如果別人做得到，那我也可以做到。我們都有個共識，若問題很困難，那就勢必不好解決。
              </p>
              <a href="#" class="btn btn-outline-light stretched-link w-100"
                >更多內容</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card text-white border-5 h-100">
            <img
              src="https://images.unsplash.com/photo-1527271982979-83fea3eb3582?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=736&q=80"
              alt=""
              class="card-img h-100 object-fit-cover"
            />
            <div class="card-img-overlay top-auto bg-dark-gradient">
              <h5 class="card-title">飲品</h5>
              <p class="card-text">
                我們不得不面對一個非常尷尬的事實，那就是，領悟其中的道理也不是那麼的困難。恩格斯說過，沒有掌握技術的人才，技術就是死。
              </p>
              <a href="#" class="btn btn-outline-light stretched-link w-100"
                >更多內容</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- footer -->
  <footer class="bg-primary text-white p-5">
    <div class="container">
      <h2 class="display-4 text-4 text-center mb-4">做個朋友吧</h2>
      <div class="row justify-content-center">
        <!-- 聯絡方式與社群關注 -->
        <div class="div col-md-5">
          <p>遇到世界上另一個地方的您相當的開心</p>
          <h3 class="h4">聯絡方式</h3>
          <ul class="list-unstyled mb-5">
            <li>
              <i class="bi bi-envelope me-2"></i
              ><a
                class="link-light text-decoration-none"
                href="mailto: yoo432@gmail.com"
                >yoo432@gmail.com</a
              >
            </li>
            <li>
              <i class="bi bi-telephone me-2"></i>
              <a class="link-light text-decoration-none" href="tel: 0976-432543"
                >0976-432543</a
              >
            </li>
          </ul>
          <h3 class="h4">社群關注</h3>
          <ul class="list-unstyled mb-5">
            <li>
              <a href="#" class="link-light text-decoration-none"
                ><i class="bi bi-instagram me-2"></i>yoo432ig</a
              >
            </li>
            <li>
              <a href="#" class="link-light text-decoration-none"
                ><i class="bi bi-facebook me-2"></i>yoo432fb</a
              >
            </li>
            <li>
              <a href="#" class="link-light text-decoration-none"
                ><i class="bi bi-twitter me-2"></i>yoo432tr</a
              >
            </li>
          </ul>
          <p>ⓒ 2022 by 陳 六角 created with Bootstrap5</p>
        </div>
        <!-- 表單 -->
        <form class="col-md-5 needs-validation" novalidate>
          <div class="row g-2">
            <div class="col-md-6">
              <div class="mb-3">
                <label for="validationServer01" class="form-label">姓氏</label>
                <input
                  type="text"
                  class="form-control"
                  id="validationServer01"
                  placeholder="Wang"
                  required
                />
              </div>
              <div class="invalid-feedback">請輸入您的姓氏</div>
              <div class="valid-feedback">OK</div>
            </div>
            <div class="col-md-6">
              <div class="mb-3">
                <label for="validationServer02" class="form-label">名字</label>
                <input
                  type="text"
                  class="form-control"
                  id="validationServer02"
                  placeholder="HAHA"
                  required
                />
                <div class="invalid-feedback">請輸入您的姓名</div>
                <div class="valid-feedback">OK</div>
              </div>
            </div>
          </div>
          <div class="mb-3 col-md-12">
            <label for="email" class="form-label">Email</label>
            <input
              type="email"
              class="form-control"
              id="email"
              placeholder="YourEmail@gmail"
              required
            />
            <div class="invalid-feedback">請輸入您的電子信箱</div>
            <div class="valid-feedback">OK</div>
          </div>
          <div class="col12 mb-3">
            <label for="textarea" class="form-label">留些訊息給我吧</label>
            <textarea
              class="form-control"
              placeholder="想說些什麼嗎? 可以在這邊留言給我喔!"
              id="textarea"
              rows="3"
            ></textarea>
          </div>
          <div class="col12 text-end">
            <button type="submit" class="btn btn-outline-light">
              送出表單
            </button>
          </div>
        </form>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
.bg-cover {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}

.bg-dark-gradient {
  background-image: linear-gradient(
    180deg,
    rgba(0, 0, 0, 0),
    rgba(0, 0, 0, 0.8)
  );
  // linear-gradient( 方向性,色彩 )
}
</style>

<script>
export default {
  mounted() {
    // 驗證表單
    const forms = document.querySelectorAll('.needs-validation');

    Array.from(forms).forEach((form) => {
      form.addEventListener(
        'submit',
        (event) => {
          if (!form.checkValidity()) {
            event.preventDefault();
            event.stopPropagation();
          }

          form.classList.add('was-validated');
        },
        false
      );
    });
  },
};
</script>
