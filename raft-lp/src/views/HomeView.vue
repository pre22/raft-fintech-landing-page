<template>
  <div class="">
    <NavBar />

    <!-- Hero section  -->
    <div class="grid gap-y-[32px] py-18 pb-30 text-center font-normal">
      <div>
        <button
          type="button"
          class="text-[#DCDCDC] bg-[#989898] px-4 py-2 border-radius-100 text-base"
        >
          Introducing Rafts Card
          <i class="fa-solid fa-chevron-right pl-[10px]"></i>
        </button>
      </div>

      <h1 class="text-white text-8xl">
        Building the future of <br />
        banking
      </h1>

      <p class="custom-text-gray text-2xl">
        Experience the future of banking with RAFT. We're here <br />
        to empower your financial journey.
      </p>

      <div>
        <button
          type="button"
          class="custom-btn-bg-green text-white py-4 px-8 font-semibold border-radius-100"
        >
          Get Started
        </button>
      </div>
    </div>

    <!-- img  -->
    <div class="width-90 flex justify-center">
      <img
        src="/src/assets/img/frame_one.png"
        alt="happy"
        style="max-height: 700px; max-width: 1360px; border-radius: 12px"
      />
    </div>

    <!-- featured section  -->
    <div class="text-center py-30">
      <p class="font-medium custom-text-gray text-xl">Featured and seen in</p>
      <div class="flex justify-center">
        <div class="flex gap-x-[80px] items-center" style="max-width: 860px; max-height: 60px">
          <img src="/src/assets/img/Forbes.svg" alt="forbes" />
          <img src="/src/assets/img/cnbc.svg" alt="cnbc" />
          <img src="/src/assets/img/bloomberg.svg" alt="bloomberg" />
          <img src="/src/assets/img/reuters.svg" alt="reuters" />
          <img src="/src/assets/img/cnn.svg" alt="cnn" />
        </div>
      </div>
    </div>

    <!-- elevate section  -->
    <div class="grid py-30 width-90x">
      <div class="grid gap-y-[32px] pb-[108px] text-center">
        <h2 class="text-8xl text-white">
          Elevate Your Financial <br />
          Journey with RAFT
        </h2>
        <p class="text-xl leading-[28px] text-[#989898]">
          RAFT offers a world of financial possibilities. From investments to payments,<br />
          we've got you covered. Join us and unlock your financial potential today.
        </p>
      </div>

      <div class="flex flex-col gap-y-5">
        <div class="flex justify-center text-left gap-x-5">
          <div class="grid gap-y-[84px] pt-[48px] lg:min-w-[822px] grid-background rounded-xl">
            <div class="flex justify-center">
              <img src="/src/assets/img/seamless_payment.svg" alt="" />
            </div>

            <div class="grid gap-y-4 p-[40px]">
              <h3 class="text-white font-semibold text-4xl">Seamless Payment</h3>
              <p class="custom-text-gray">
                Enjoy secure, seamless transactions that make managing your money a <br />
                breeze.
              </p>
            </div>
          </div>

          <div class="grid gap-y-[84px] pt-[48px] grid-background bg-[#131313] rounded-xl">
            <div class="flex justify-right pl-[33px] pt-[54px]">
              <img src="/src/assets/img/smart_investment.svg" alt="" />
            </div>

            <div class="grid gap-y-4 p-[40px]">
              <h3 class="text-white font-semibold text-4xl">Smart Investing</h3>
              <p class="custom-text-gray">
                Grow your wealth confidently with our personalized <br />
                investment solutions, tailored to your financial goals.
              </p>
            </div>
          </div>
        </div>

        <div class="flex justify-center text-left gap-x-5">
          <div class="grid gap-y-[84px] pt-[48px] grid-background bg-[#131313] rounded-xl">
            <div class="flex justify-center pl-[33px] pt-[54px]">
              <img src="/src/assets/img/frame_106.svg" alt="" />
            </div>

            <div class="grid gap-y-4 p-[40px]">
              <h3 class="text-white font-semibold text-4xl">Wealth Management</h3>
              <p class="custom-text-gray">
                Make informed decisions for your financial future with <br />
                our wealth management expertise.
              </p>
            </div>
          </div>

          <div class="grid gap-y-[84px] pt-[48px] lg:min-w-[822px] grid-background rounded-xl">
            <div class="flex justify-center">
              <img src="/src/assets/img/Group_8.svg" alt="" />
            </div>

            <div class="grid gap-y-4 p-[40px]">
              <h3 class="text-white font-semibold text-4xl">Financial Planning</h3>
              <p class="custom-text-gray">
                Achieve your financial dreams with our comprehensive financial planning <br />
                services, guiding you toward a secure future.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- freedom section  -->
    <div class="grid text-center py-30 width-90x">
      <div class="grid gap-y-[32px] pb-[124px]">
        <h2 class="text-[76px] text-white">
          Your Financial Freedom,<br />
          Your Way
        </h2>
        <p class="text-xl leading-[28px] text-[#989898]">
          We believe that managing your finances should be effortless and cost-effective. <br />
          That's why we offer you the freedom you deserve
        </p>
      </div>

      <div class="flex flex-col gap-y-[80px]">
        <div class="flex justify-center">
          <img
            src="/src/assets/img/Frame_31.png"
            alt="happy"
            style="max-height: 615px; max-width: 1296px; border-radius: 12px"
          />
        </div>

        <!-- content  -->
        <div class="text-white text-left flex gap-3 justify-center">
          <div class="grid gap-y-3">
            <!-- first row -->
            <div class="flex items-center gap-x-2">
              <!-- icon  -->
              <i class="fa-solid fa-money-bills"></i>
              <p>No minimum balance fees</p>
            </div>
            <!-- second row  -->
            <div>
              <p class="text-base custom-text-gray leading-[24px]">
                Say goodbye to minimum balance fees. Your account, your <br />
                balance—no hidden charges
              </p>
            </div>
          </div>

          <div class="grid gap-y-3">
            <!-- first row -->
            <div class="flex items-center gap-x-2">
              <!-- icon  -->
              <i class="fa-solid fa-coins"></i>
              <p>No monthly fees</p>
            </div>
            <!-- second row  -->
            <div>
              <p class="text-base custom-text-gray leading-[24px]">
                Bank with us without worrying about monthly fees. Keep more <br />
                of your money where it belongs—in your account
              </p>
            </div>
          </div>

          <div class="grid gap-y-3">
            <!-- first row -->
            <div class="flex items-center gap-x-2">
              <!-- icon  -->
              <i class="fa-solid fa-right-left"></i>
              <p>No bank transfer fees</p>
            </div>
            <!-- second row  -->
            <div>
              <p class="text-base custom-text-gray leading-[24px]">
                Seamlessly transfer funds without the extra cost. Send and <br />
                receive money with zero bank transfer fees.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- smart investment  -->
    <div class="bg-[#48D64C] py-[132px]">
      <div class="width-90">
        <h2 class="text-9xl text-[#070606] text-left">
          Smart investments,<br />
          secure payments,<br />
          and expert guidance, all in one place.
        </h2>
      </div>
    </div>

    <!-- confi section  -->
    <div class="grid pt-[124px] pb-[100px] width-90x">
      <div class="grid gap-y-[24px] pb-[100px] text-left">
        <h2 class="text-7xl text-white">
          Confidently Shape Your <br />
          Financial Future
        </h2>
        <p class="text-xl leading-[28px] text-[#989898]">
          At RAFT, we empower you to confidently shape your financial future.Our modern <br />
          approach simplifies saving and investing, making it easier than ever.
        </p>
      </div>

      <div class="flex justify-around text-left">
        <div class="grid gap-y-[84px] p-[40px] grid-background bg-[#131313] rounded-xl">
          <div class="grid gap-y-4">
            <h3 class="text-white font-semibold text-4xl">Spend better</h3>
            <p class="custom-text-gray">
              Set and achieve financial goals with ease, automate your <br />
              savings, and watch your money grow without the stress.
            </p>
          </div>

          <div class="flex justify-center">
            <img src="/src/assets/img/money-send.svg" alt="" />
          </div>
        </div>

        <div class="grid gap-y-[84px] p-[40px] grid-background bg-[#131313] rounded-xl">
          <div class="grid gap-y-4">
            <h3 class="text-white font-semibold text-4xl">Invest better</h3>
            <p class="custom-text-gray">
              Set and achieve financial goals with ease, automate your <br />
              savings, and watch your money grow without the stress.
            </p>
          </div>

          <div class="flex justify-center">
            <img src="/src/assets/img/wallet-minus.svg" alt="" />
          </div>
        </div>
      </div>
    </div>

    <!-- stats  -->
    <div class="flex justify-between text-white text-center width-90">
      <div class="flex flex-col gap-y-4">
        <p class="font-semibold text-[80px] leading-none">50+</p>
        <p class="uppercase font-medium custom-text-gray">cities</p>
      </div>
      <div class="flex flex-col gap-y-4">
        <p class="font-semibold text-[80px] leading-none">50,000+</p>
        <p class="uppercase font-medium custom-text-gray">transactions</p>
      </div>
      <div class="flex flex-col gap-y-4">
        <p class="font-semibold text-[80px] leading-none">3M+</p>
        <p class="uppercase font-medium custom-text-gray">users</p>
      </div>
      <div class="flex flex-col gap-y-4">
        <p class="font-semibold text-[80px] leading-none">5</p>
        <p class="uppercase font-medium custom-text-gray">user ratings</p>
      </div>
    </div>

    <!-- img -->
    <div class="flex justify-center py-[100px]">
      <img
        src="/src/assets/img/frame_150.svg"
        alt="happy"
        style="max-height: 848px; max-width: 1440px"
      />
    </div>

    <!-- introducing  -->
    <div class="grid text-center py-[120px] width-90x">
      <div class="grid gap-y-[32px]">
        <p class="font-semibold text-lg text-[#48D64C] text-center uppercase leading-1">
          Introducing
        </p>
        <h2 class="text-[76px] text-white">
          Introducing RAFT's Next-Gen <br />
          Cards
        </h2>
        <p class="text-xl leading-28px text-[#989898]">
          Discover RAFT's latest innovation – our new cards. Elevate your banking <br />
          experience with cutting-edge features, security, and unprecedented <br />
          convenience.
        </p>
      </div>

      <div class="flex flex-col gap-y-[80px]">
        <div class="flex justify-center py-[124px]">
          <img
            src="/src/assets/img/Frame_122.svg"
            alt="happy"
            style="max-height: 615px; max-width: 1296px; border-radius: 12px"
          />
        </div>

        <!-- content  -->
        <div class="text-white text-left flex gap-3 justify-center">
          <div class="grid gap-y-3">
            <!-- first row -->
            <div class="flex items-center gap-x-2">
              <!-- icon  -->
              <i class="fa-solid fa-copy"></i>
              <p>Contactless Technology</p>
            </div>
            <!-- second row  -->
            <div>
              <p class="text-base custom-text-gray leading-[24px]">
                Our new cards come equipped with contactless technology, <br />
                allowing you to make swift, secure payments with a simple tap.
              </p>
            </div>
          </div>

          <div class="grid gap-y-3">
            <!-- first row -->
            <div class="flex items-center gap-x-2">
              <!-- icon  -->
              <i class="fa-solid fa-address-card"></i>
              <p>Personalization</p>
            </div>
            <!-- second row  -->
            <div>
              <p class="text-base custom-text-gray leading-[24px]">
                Customize your card to reflect your unique style. Choose from <br />
                a range of designs that suit your personality.
              </p>
            </div>
          </div>

          <div class="grid gap-y-3">
            <!-- first row -->
            <div class="flex items-center gap-x-2">
              <!-- icon  -->
              <i class="fa-solid fa-lock"></i>
              <p>Enhanced Security</p>
            </div>
            <!-- second row  -->
            <div>
              <p class="text-base custom-text-gray leading-[24px]">
                Your peace of mind is our priority. Our cards feature advanced <br />
                security measures to protect your transactions and data.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- faqs  -->
    <!-- <div class="text-white width-90x">
      <h2 class="text-8xl text-left">
        Frequently asked <br />
        questions
      </h2>
    </div> -->

    <AppFooter class="width-90" />
  </div>
</template>

<script setup>
import AppFooter from '@/components/AppFooter.vue'
import NavBar from '@/components/NavBar.vue'
</script>
