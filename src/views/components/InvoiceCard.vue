<template>
  <div class="card h-100 mt-4">
    <div class="card-header pb-0 p-3">
      <div class="row">
        <div class="col-6 d-flex align-items-center">
          <h6 class="mb-0">Счета</h6>
        </div>
        <div class="col-6 text-end">
          <soft-button color="success" size="sm" variant="outline"
            >Просмотреть все</soft-button
          >
        </div>
      </div>
    </div>
    <div class="card-body p-3 pb-0 mb-0">
      <ul class="list-group">
        <li
          class="list-group-item border-0 d-flex justify-content-between ps-0 mb-2 border-radius-lg"
        >
          <div class="d-flex flex-column">
            <h6 class="mb-1 text-dark font-weight-bold text-sm">
              Март, 01, 2020
            </h6>
            <span class="text-xs">#MS-415646</span>
          </div>
          <div class="d-flex align-items-center text-sm">
            18542 ₽
            <button class="btn btn-link text-dark text-sm mb-0 px-0 ms-4">
              <i class="fas fa-file-pdf text-lg me-1" aria-hidden="true"></i>
              PDF
            </button>
          </div>
        </li>
        <li
          class="list-group-item border-0 d-flex justify-content-between ps-0 mb-2 border-radius-lg"
        >
          <div class="d-flex flex-column">
            <h6 class="text-dark mb-1 font-weight-bold text-sm">
              Февраль, 10, 2021
            </h6>
            <span class="text-xs">#RV-126749</span>
          </div>
          <div class="d-flex align-items-center text-sm">
            25000 ₽
            <button class="btn btn-link text-dark text-sm mb-0 px-0 ms-4">
              <i class="fas fa-file-pdf text-lg me-1" aria-hidden="true"></i>
              PDF
            </button>
          </div>
        </li>
        <li
          class="list-group-item border-0 d-flex justify-content-between ps-0 mb-2 border-radius-lg"
        >
          <div class="d-flex flex-column">
            <h6 class="text-dark mb-1 font-weight-bold text-sm">
              Апрель, 05, 2020
            </h6>
            <span class="text-xs">#FB-212562</span>
          </div>
          <div class="d-flex align-items-center text-sm">
            56000 ₽
            <button class="btn btn-link text-dark text-sm mb-0 px-0 ms-4">
              <i class="fas fa-file-pdf text-lg me-1" aria-hidden="true"></i>
              PDF
            </button>
          </div>
        </li>
        <li
          class="list-group-item border-0 d-flex justify-content-between ps-0 mb-2 border-radius-lg"
        >
          <div class="d-flex flex-column">
            <h6 class="text-dark mb-1 font-weight-bold text-sm">
              Июнь, 25, 2019
            </h6>
            <span class="text-xs">#QW-103578</span>
          </div>
          <div class="d-flex align-items-center text-sm">
            14250 ₽
            <button class="btn btn-link text-dark text-sm mb-0 px-0 ms-4">
              <i class="fas fa-file-pdf text-lg me-1" aria-hidden="true"></i>
              PDF
            </button>
          </div>
        </li>
        <li
          class="list-group-item border-0 d-flex justify-content-between ps-0 border-radius-lg"
        >
          <div class="d-flex flex-column">
            <h6 class="text-dark mb-1 font-weight-bold text-sm">
              Март, 01, 2019
            </h6>
            <span class="text-xs">#AR-803481</span>
          </div>
          <div class="d-flex align-items-center text-sm">
            31200 ₽
            <button class="btn btn-link text-dark text-sm mb-0 px-0 ms-4">
              <i class="fas fa-file-pdf text-lg me-1" aria-hidden="true"></i>
              PDF
            </button>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import SoftButton from "@/components/SoftButton.vue";

export default {
  name: "InvoiceCard",
  components: {
    SoftButton,
  },
};
</script>
