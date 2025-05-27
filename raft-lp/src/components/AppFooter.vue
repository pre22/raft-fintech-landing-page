<template>
  <footer class="text-white grid gap-[60px]">
    <div class="flex">
      <img
        class="max-w-sm min-w-[212px] max-h-[153px] min-h-[86px]"
        src="/src/assets/img/raft.svg"
        alt="Raft"
        srcset=""
      />
    </div>

    <div class="flex justify-between pt-[52px] border-t-1 border-[#3D3D3D]">
      <!-- qr  -->
      <div class="flex gap-3 px-4 py-5 rounded-xl border-2 border-dashed lg:min-w-[457px]">
        <div>
          <img src="/src/assets/img/qr_code_download.svg" alt="download_qr_code" />
        </div>

        <div class="flex flex-col gap-4">
          <div>
            <p>
              Scan to download App on the <br />
              Playstore and Appstore.
            </p>
          </div>
          <div class="flex">
            <img src="/src/assets/img/playstore_logo.svg" alt="android" />
            <img src="/src/assets/img/apple_logo.svg" alt="ios" />
          </div>
        </div>
      </div>

      <!-- categories  -->
      <div class="grid grid-cols-3 gap-[52px]">
        <!-- about us  -->
        <div class="grid gap-4">
          <h6>About US</h6>
          <p>Our Company</p>
          <p>Careers</p>
          <p>Press Kits</p>
        </div>

        <!-- Legal  -->
        <div class="grid gap-4">
          <h6>Legal</h6>
          <p>Terms of use</p>
          <p>Privacy Policy</p>
          <p>About US</p>
        </div>

        <!-- Support  -->
        <div class="grid gap-4">
          <h6>Support</h6>
          <p>Contact us</p>
          <p>FAQ</p>
        </div>
      </div>
    </div>

    <div class="flex justify-between">
      <button>English (United Kingdom) <i class="fa-solid fa-chevron-down pl-[10px]"></i></button>
      <p class="flex gap-x-2"><i class="fa-regular fa-copyright"></i>Raft Corp, LLC.</p>
    </div>
  </footer>
</template>
