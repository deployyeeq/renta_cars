<template>
  <div class="card mt-4">
    <div class="card-header pb-0 p-3">
      <div class="row">
        <div class="col-6 d-flex align-items-center">
          <h6 class="mb-0">Способы оплаты</h6>
        </div>
        <div class="col-6 text-end">
          <soft-button color="dark" variant="gradient">
            <i class="fas fa-plus me-2"></i>
            Добавить новую карту
          </soft-button>
        </div>
      </div>
    </div>
    <div class="card-body p-3">
      <div class="row">
        <div class="col-md-6 mb-md-0 mb-4">
          <div
            class="card card-body border card-plain border-radius-lg d-flex align-items-center flex-row"
          >
            <img
              class="w-10 me-3 mb-0"
              src="@/assets/img/logos/mastercard.png"
              alt="logo"
            />
            <h6 class="mb-0">
              ****&nbsp;&nbsp;&nbsp;****&nbsp;&nbsp;&nbsp;****&nbsp;&nbsp;&nbsp;7852
            </h6>
            <i
              class="fas fa-pencil-alt ms-auto text-dark cursor-pointer"
              data-bs-toggle="tooltip"
              data-bs-placement="top"
              title
              aria-hidden="true"
              data-bs-original-title="Редактировать карту"
              aria-label="Редактировать карту"
            ></i>
            <span class="sr-only">Редактировать карту</span>
          </div>
        </div>
        <div class="col-md-6">
          <div
            class="card card-body border card-plain border-radius-lg d-flex align-items-center flex-row"
          >
            <img
              class="w-10 me-3 mb-0"
              src="@/assets/img/logos/mir2.png"
              alt="logo"
            />
            <h6 class="mb-0">
              ****&nbsp;&nbsp;&nbsp;****&nbsp;&nbsp;&nbsp;****&nbsp;&nbsp;&nbsp;5248
            </h6>
            <i
              class="fas fa-pencil-alt ms-auto text-dark cursor-pointer"
              data-bs-toggle="tooltip"
              data-bs-placement="top"
              title
              aria-hidden="true"
              data-bs-original-title="Редактировать карту"
              aria-label="Редактировать карту"
            ></i>
            <span class="sr-only">Редактировать карту</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SoftButton from "@/components/SoftButton.vue";
import img1 from "@/assets/img/logos/mastercard.png";
import img2 from "@/assets/img/logos/visa.png";

export default {
  name: "PaymentMethodsCard",
  components: {
    SoftButton,
  },
  data() {
    return {
      img1,
      img2,
    };
  },
};
</script>
