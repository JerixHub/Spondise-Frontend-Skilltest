<template>
  <div>
    <div class="container-fluid nav-container">
      <div class="container">
        <nav class="navbar navbar-expand-lg navbar-light">
          <div class="container-fluid">
            <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div
              class="collapse navbar-collapse justify-content-between"
              id="navbarSupportedContent"
            >
              <a class="navbar-brand" href="#">
                <img src="/images/logo.png" alt="brand-logo" />
              </a>
              <ul class="navbar-nav">
                <div class="input-group justify-content-center">
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Filter"
                    aria-label="Filter"
                    style="max-width: 20%; border-right: 0px"
                  />
                  <button
                    class="btn btn-outline-secondary"
                    type="button"
                    id="button-addon1"
                  >
                    <img src="/images/filter-icon.png" />
                  </button>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Smart Search"
                    aria-label="Smart Search"
                    style="max-width: 20%; border-right: 0px"
                  />
                  <button
                    class="btn btn-outline-secondary"
                    type="button"
                    id="button-addon2"
                  >
                    <img src="/images/search-icon.png" />
                  </button>
                </div>
              </ul>

              <ul
                class="navbar-nav justify-content-end align-items-center mb-2 mb-lg-0"
              >
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">
                    <svg
                      width="18"
                      height="22"
                      viewBox="0 0 18 22"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M13.1205 0.6875L17.2505 4.8125V21.3125H0.750488V0.6875H13.1205Z"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-linejoin="round"
                      />
                      <path
                        d="M13.1206 0.6875V4.8125H17.2506"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-linejoin="round"
                      />
                      <path
                        d="M12.4406 10.3125H5.56073"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-linejoin="round"
                      />
                      <path
                        d="M14.5004 13.75H3.50043"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-linejoin="round"
                      />
                      <path
                        d="M12.4406 17.1875H5.56073"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-linejoin="round"
                      />
                    </svg>
                  </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">
                    <svg
                      width="22"
                      height="24"
                      viewBox="0 0 22 24"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M20.5904 17.85L19.6904 16.4688C18.1504 14.1938 17.3404 11.5125 17.3404 8.75C17.3404 5.825 15.3905 3.4688 12.7905 2.6562C12.5405 1.925 11.8104 1.4375 11.0004 1.4375C10.1904 1.4375 9.46038 1.925 9.21038 2.6562C6.61038 3.4688 4.66045 5.825 4.66045 8.75C4.66045 11.5125 3.85048 14.1938 2.31048 16.4688L1.41046 17.85C1.01046 18.5 1.4104 19.3125 2.2304 19.3125H19.7804C20.5904 19.3125 20.9904 18.5 20.5904 17.85Z"
                        stroke="black"
                        stroke-width="1.6"
                        stroke-miterlimit="10"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      />
                      <path
                        d="M14.2495 19.3125C14.2495 21.1 12.7895 22.5625 10.9995 22.5625C9.20951 22.5625 7.74951 21.1 7.74951 19.3125"
                        stroke="black"
                        stroke-width="1.6"
                        stroke-miterlimit="10"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      />
                    </svg>
                  </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">
                    <svg
                      width="25"
                      height="21"
                      viewBox="0 0 25 21"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M20.0901 19.7812H4.91016C3.05016 19.7812 1.53015 18.2625 1.53015 16.4062V4.59381C1.53015 2.73751 3.05016 1.21881 4.91016 1.21881H20.0901C21.9501 1.21881 23.4701 2.73751 23.4701 4.59381V16.4062C23.4701 18.2625 21.9501 19.7812 20.0901 19.7812Z"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-miterlimit="10"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      />
                      <path
                        d="M1.53015 5.4375L12.5001 12.1875L23.4701 5.4375"
                        stroke="black"
                        stroke-width="1.5"
                        stroke-miterlimit="10"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      />
                    </svg>
                  </a>
                </li>
                <div class="profile-dropdown">
                  <span>Sponsor</span>
                  <img src="/images/profile.png" />
                </div>
              </ul>
            </div>
          </div>
        </nav>
      </div>
    </div>
    <div class="container-fluid breadcrumb-progress-container">
      <div class="container mt-3 breadcrumb-container">
        <nav
          style="--bs-breadcrumb-divider: '>'"
          aria-label="breadcrumb"
          class="my-breadcrumb"
        >
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Dashboard</a></li>
            <li class="breadcrumb-item" aria-current="page">
              <a href="#">Sponsor Profile</a>
            </li>
            <li class="breadcrumb-item" aria-current="page">Verification</li>
          </ol>
        </nav>
        <div class="switch">
          <div class="form-check form-switch">
            <span>Sponsor</span>
            <input class="form-check-input" type="checkbox" checked />
            <span>Creator</span>
          </div>
        </div>
        <div class="progress-bar-container">
          <div class="progress-bar-label">
            <span>Profile Completeness</span><span>90%</span>
          </div>
          <div class="progress-bar-level">
            <div class="progress">
              <div
                class="progress-bar bg-warning"
                role="progressbar"
                style="width: 90%"
                aria-valuenow="90"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container profile-main">
      <div class="row">
        <div class="col-12 col-sm-4">
          <div class="profile-name-image">
            <img src="/images/profile.png" />
            <div class="profile-name">
              <span>Jhonny_Official</span>
              <svg
                width="15"
                height="15"
                viewBox="0 0 15 15"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <mask
                  id="mask0_1_198"
                  style="mask-type: luminance"
                  maskUnits="userSpaceOnUse"
                  x="0"
                  y="0"
                  width="16"
                  height="15"
                >
                  <path d="M15.0007 0H0.000732422V15H15.0007V0Z" fill="white" />
                </mask>
                <g mask="url(#mask0_1_198)">
                  <path
                    d="M14.4295 4.371C14.7055 4.166 14.6725 3.73699 14.4295 3.49399L11.4975 0.562011C11.2545 0.319011 10.8635 0.319011 10.6205 0.562011L5.86554 5.30899L1.11652 10.05C0.871516 11.57 0.619512 13.097 0.374512 14.617L4.9245 13.859C7.3845 11.399 8.54752 10.241 9.72052 9.07199C10.8935 7.90299 12.0475 6.754 14.4295 4.371Z"
                    stroke="black"
                    stroke-width="1.5"
                    stroke-miterlimit="6.2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                  <path
                    d="M3.09351 14.55L0.478516 11.935L0.374512 14.617L3.09351 14.55Z"
                    fill="black"
                  />
                </g>
              </svg>
            </div>
            <ul class="profile-badges">
              <li>
                <span>Sponsor Level</span>
                <svg
                  width="27"
                  height="27"
                  viewBox="0 0 27 27"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M13.4993 26.5C20.679 26.5 26.4993 20.6797 26.4993 13.5C26.4993 6.3203 20.679 0.5 13.4993 0.5C6.31956 0.5 0.499268 6.3203 0.499268 13.5C0.499268 20.6797 6.31956 26.5 13.4993 26.5Z"
                    fill="#3ABEFF"
                    stroke="white"
                  />
                  <path
                    d="M12.4201 10.166H7.7301V12.952C7.9261 12.691 8.21514 12.471 8.59814 12.294C8.99014 12.117 9.40512 12.028 9.84412 12.028C10.6281 12.028 11.2631 12.196 11.7481 12.532C12.2431 12.868 12.5931 13.293 12.7981 13.806C13.0131 14.319 13.1201 14.861 13.1201 15.43C13.1201 16.121 12.9851 16.737 12.7141 17.278C12.4531 17.81 12.0561 18.23 11.5241 18.538C11.0011 18.846 10.3571 19 9.5921 19C8.5751 19 7.75815 18.748 7.14215 18.244C6.52615 17.74 6.15713 17.073 6.03613 16.242H7.59015C7.69315 16.681 7.92112 17.031 8.27612 17.292C8.63112 17.544 9.07414 17.67 9.60614 17.67C10.2691 17.67 10.7631 17.469 11.0901 17.068C11.4261 16.667 11.5941 16.135 11.5941 15.472C11.5941 14.8 11.4261 14.287 11.0901 13.932C10.7541 13.568 10.2591 13.386 9.60614 13.386C9.14914 13.386 8.76109 13.503 8.44409 13.736C8.13609 13.96 7.91209 14.268 7.77209 14.66H6.26013V8.76599H12.4201V10.166ZM21.2491 10.026L17.3571 19H15.7471L19.6811 10.194H14.5011V8.836H21.2491V10.026Z"
                    fill="white"
                  />
                </svg>
              </li>
              <li>
                <span>Sponsor Plan</span>
                <svg
                  width="27"
                  height="27"
                  viewBox="0 0 27 27"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M13.4993 26.5C20.679 26.5 26.4993 20.6797 26.4993 13.5C26.4993 6.3203 20.679 0.5 13.4993 0.5C6.31956 0.5 0.499268 6.3203 0.499268 13.5C0.499268 20.6797 6.31956 26.5 13.4993 26.5Z"
                    fill="#3ABEFF"
                    stroke="white"
                  />
                  <path
                    d="M20.9138 7.25H17.5388C17.5258 7.25 17.5158 7.25599 17.5038 7.25699C17.1378 6.62499 16.7348 6.27601 16.7058 6.25201C16.6048 6.17001 16.4788 6.125 16.3488 6.125H10.8518C10.7218 6.125 10.5958 6.16999 10.4958 6.25299C10.4668 6.27699 10.0638 6.62499 9.69779 7.25699C9.68579 7.25599 9.67579 7.25 9.66379 7.25H6.2888C6.1278 7.25 5.97579 7.31801 5.86979 7.43701C5.76279 7.55701 5.7118 7.71599 5.7288 7.87399C5.9208 9.59599 7.17278 12.902 10.5188 13.373C10.8828 13.893 11.3128 14.418 11.8188 14.95C11.8458 14.978 11.8818 14.993 11.9128 15.015V16.25H10.7878C10.4778 16.25 10.2257 16.501 10.2257 16.812V18.5H9.10075C8.79075 18.5 8.53879 18.751 8.53879 19.062V21.312C8.53879 21.624 8.79075 21.875 9.10075 21.875H18.1007C18.4117 21.875 18.6638 21.624 18.6638 21.312V19.062C18.6638 18.751 18.4117 18.5 18.1007 18.5H16.9757V16.812C16.9757 16.501 16.7238 16.25 16.4138 16.25H15.2888V15.016C15.3208 14.994 15.3558 14.978 15.3828 14.95C15.8878 14.419 16.3178 13.893 16.6828 13.373C20.0278 12.903 21.2808 9.597 21.4718 7.875C21.4898 7.716 21.4388 7.55699 21.3318 7.43799C21.2258 7.31799 21.0738 7.25 20.9138 7.25ZM6.96476 8.375H9.24674C9.18174 8.63 9.12878 8.899 9.10978 9.198C9.05278 10.104 9.25479 11.042 9.71079 12.007C7.89279 11.271 7.20476 9.373 6.96476 8.375ZM17.5388 20.75H9.66379V19.625H10.7888H16.4138H17.5388V20.75ZM15.8507 18.5H11.3507V17.375H12.4757H14.7257H15.8507V18.5ZM13.0388 16.25V15.125H14.1638V16.25H13.0388ZM14.7318 14H14.7257H12.4757H12.4698C10.9048 12.302 10.1518 10.719 10.2318 9.29199C10.2918 8.20999 10.8248 7.519 11.0778 7.25H16.1238C16.3778 7.521 16.9098 8.211 16.9698 9.293C17.0498 10.719 16.2968 12.302 14.7318 14ZM17.4937 12.003C17.9477 11.04 18.1488 10.102 18.0918 9.19699C18.0738 8.89899 18.0208 8.63 17.9558 8.375H20.2318C19.9868 9.368 19.2887 11.264 17.4937 12.003Z"
                    fill="white"
                  />
                </svg>
              </li>
              <li>
                <span>Verified</span>
                <svg
                  width="21"
                  height="21"
                  viewBox="0 0 21 21"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M10.5937 20.056C15.8199 20.056 20.0566 15.8192 20.0566 10.593C20.0566 5.36674 15.8199 1.13004 10.5937 1.13004C5.36744 1.13004 1.13074 5.36674 1.13074 10.593C1.13074 15.8192 5.36744 20.056 10.5937 20.056Z"
                    fill="#C13515"
                    stroke="white"
                  />
                  <path
                    d="M15.0209 14.08L11.9409 11L15.0209 7.92002C15.3539 7.58802 15.3539 7.05301 15.0209 6.72001C14.6889 6.38801 14.1529 6.38801 13.8209 6.72001L10.7409 9.79999L7.66093 6.72001C7.32893 6.38801 6.79391 6.38801 6.46091 6.72001C6.12891 7.05301 6.12891 7.58802 6.46091 7.92002L9.54093 11L6.46091 14.08C6.12891 14.412 6.12891 14.948 6.46091 15.28C6.79391 15.613 7.32893 15.613 7.66093 15.28L10.7409 12.2L13.8209 15.28C14.1529 15.613 14.6889 15.613 15.0209 15.28C15.3509 14.948 15.3509 14.41 15.0209 14.08Z"
                    fill="white"
                  />
                </svg>
              </li>
              <li>
                <span>Ratings</span>
                <span
                  ><svg
                    width="20"
                    height="20"
                    viewBox="0 0 20 20"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <mask
                      id="mask0_1_178"
                      style="mask-type: luminance"
                      maskUnits="userSpaceOnUse"
                      x="-1"
                      y="0"
                      width="21"
                      height="20"
                    >
                      <path
                        d="M19.9994 0H-0.000610352V20H19.9994V0Z"
                        fill="white"
                      />
                    </mask>
                    <g mask="url(#mask0_1_178)">
                      <path
                        d="M10.0002 1.42099L12.2783 7.328L18.6002 7.66901L13.6862 11.66L15.3152 17.778L10.0002 14.339L4.68524 17.778L6.31427 11.66L1.40027 7.66901L7.72223 7.328L10.0002 1.42099Z"
                        stroke="#222222"
                        stroke-miterlimit="10"
                      />
                    </g></svg
                  >5.0</span
                >
              </li>
              <li>
                <span>Completed Contracts</span>
                <span>14</span>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-12 col-sm-8">
          <div class="verify-country-container">
            <div class="floating-label-container">
              <span>Verify Phone Number</span>
              <div class="form-check form-switch">
                <input class="form-check-input" type="checkbox" checked />
              </div>
            </div>
            <div class="verify-phone-container">
              <div class="row">
                <div class="col-6">
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Select country code"
                  />
                </div>
                <div class="col-6">
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Phone number"
                  />
                </div>
              </div>
            </div>
          </div>
          <div class="verify-email-container mt-3">
            <div class="floating-label-container">
              <span>Verify Email</span>
              <div class="form-check form-switch">
                <input type="checkbox" class="form-check-input" checked />
              </div>
            </div>
            <div class="verify-phone-container">
              <input type="text" class="form-control" placeholder="Email" />
            </div>
          </div>
          <div class="verify-identity-container mt-3">
            <div class="floating-label-container">
              <span>Verify Identity</span>
              <div class="form-check form-switch">
                <input type="checkbox" class="form-check-input" checked />
              </div>
            </div>
            <div class="verify-phone-container">
              <div class="row verify-id-inner-container">
                <span class="inner-title"
                  >Choose an ID type to add
                  <a href="#">
                    <svg
                      width="15"
                      height="15"
                      viewBox="0 0 15 15"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <mask
                        id="mask0_1_146"
                        style="mask-type: luminance"
                        maskUnits="userSpaceOnUse"
                        x="0"
                        y="0"
                        width="16"
                        height="15"
                      >
                        <path
                          d="M15.0001 0H0.00012207V15H15.0001V0Z"
                          fill="white"
                        />
                      </mask>
                      <g mask="url(#mask0_1_146)">
                        <path
                          d="M15.0001 7.5C15.0001 9.489 14.2101 11.397 12.8031 12.803C11.3971 14.21 9.48912 15 7.50012 15C5.51112 15 3.60314 14.21 2.19714 12.803C0.790144 11.397 0.00012207 9.489 0.00012207 7.5C0.00012207 5.511 0.790144 3.60299 2.19714 2.19699C3.60314 0.789991 5.51112 0 7.50012 0C9.48912 0 11.3971 0.789991 12.8031 2.19699C14.2101 3.60299 15.0001 5.511 15.0001 7.5ZM5.1521 5.65601H5.92615C6.05515 5.65601 6.15811 5.55 6.17511 5.422C6.26011 4.807 6.68211 4.358 7.43311 4.358C8.07711 4.358 8.6651 4.68 8.6651 5.453C8.6651 6.049 8.31511 6.32301 7.76111 6.73901C7.13011 7.19701 6.63014 7.73299 6.66614 8.60199L6.66815 8.80499C6.66915 8.86699 6.6951 8.92499 6.7381 8.96799C6.7821 9.01099 6.84114 9.03601 6.90314 9.03601H7.66315C7.72515 9.03601 7.7851 9.01101 7.8291 8.96701C7.8731 8.92301 7.89813 8.863 7.89813 8.80099V8.703C7.89813 8.03 8.15312 7.834 8.84412 7.31C9.41512 6.876 10.0111 6.39399 10.0111 5.38199C10.0111 3.96599 8.81413 3.28101 7.50513 3.28101C6.31713 3.28101 5.01612 3.83401 4.92712 5.42401C4.92512 5.45501 4.9301 5.485 4.9411 5.513C4.9521 5.541 4.96811 5.56699 4.99011 5.58899C5.01111 5.61099 5.03615 5.62801 5.06415 5.63901C5.09215 5.65101 5.1221 5.65601 5.1521 5.65601ZM7.33209 11.696C7.90409 11.696 8.29712 11.327 8.29712 10.827C8.29712 10.31 7.90309 9.94601 7.33209 9.94601C6.78509 9.94601 6.38611 10.31 6.38611 10.827C6.38611 11.327 6.78513 11.696 7.33313 11.696H7.33209Z"
                          fill="#888888"
                        />
                      </g>
                    </svg> </a
                ></span>
                <div class="col-6">
                  <select name="country" id="country" class="form-control">
                    <option value="0" selected disabled>
                      Issuing country/region
                    </option>
                    <option value="1">PH</option>
                  </select>
                </div>
                <div class="col-6">
                  <select
                    name="identification"
                    id="identification"
                    class="form-control"
                  >
                    <option value="0" selected disabled>
                      Choose identification
                    </option>
                    <option value="1">SSS</option>
                  </select>
                </div>
              </div>
              <div class="row upload-image">
                <span class="inner-title"
                  >Upload images of your ID
                  <a href="#">
                    <svg
                      width="15"
                      height="15"
                      viewBox="0 0 15 15"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <mask
                        id="mask0_1_146"
                        style="mask-type: luminance"
                        maskUnits="userSpaceOnUse"
                        x="0"
                        y="0"
                        width="16"
                        height="15"
                      >
                        <path
                          d="M15.0001 0H0.00012207V15H15.0001V0Z"
                          fill="white"
                        />
                      </mask>
                      <g mask="url(#mask0_1_146)">
                        <path
                          d="M15.0001 7.5C15.0001 9.489 14.2101 11.397 12.8031 12.803C11.3971 14.21 9.48912 15 7.50012 15C5.51112 15 3.60314 14.21 2.19714 12.803C0.790144 11.397 0.00012207 9.489 0.00012207 7.5C0.00012207 5.511 0.790144 3.60299 2.19714 2.19699C3.60314 0.789991 5.51112 0 7.50012 0C9.48912 0 11.3971 0.789991 12.8031 2.19699C14.2101 3.60299 15.0001 5.511 15.0001 7.5ZM5.1521 5.65601H5.92615C6.05515 5.65601 6.15811 5.55 6.17511 5.422C6.26011 4.807 6.68211 4.358 7.43311 4.358C8.07711 4.358 8.6651 4.68 8.6651 5.453C8.6651 6.049 8.31511 6.32301 7.76111 6.73901C7.13011 7.19701 6.63014 7.73299 6.66614 8.60199L6.66815 8.80499C6.66915 8.86699 6.6951 8.92499 6.7381 8.96799C6.7821 9.01099 6.84114 9.03601 6.90314 9.03601H7.66315C7.72515 9.03601 7.7851 9.01101 7.8291 8.96701C7.8731 8.92301 7.89813 8.863 7.89813 8.80099V8.703C7.89813 8.03 8.15312 7.834 8.84412 7.31C9.41512 6.876 10.0111 6.39399 10.0111 5.38199C10.0111 3.96599 8.81413 3.28101 7.50513 3.28101C6.31713 3.28101 5.01612 3.83401 4.92712 5.42401C4.92512 5.45501 4.9301 5.485 4.9411 5.513C4.9521 5.541 4.96811 5.56699 4.99011 5.58899C5.01111 5.61099 5.03615 5.62801 5.06415 5.63901C5.09215 5.65101 5.1221 5.65601 5.1521 5.65601ZM7.33209 11.696C7.90409 11.696 8.29712 11.327 8.29712 10.827C8.29712 10.31 7.90309 9.94601 7.33209 9.94601C6.78509 9.94601 6.38611 10.31 6.38611 10.827C6.38611 11.327 6.78513 11.696 7.33313 11.696H7.33209Z"
                          fill="#888888"
                        />
                      </g>
                    </svg> </a
                ></span>
                <div class="col-6">
                  <div class="upload-box">
                    <svg
                      width="52"
                      height="29"
                      viewBox="0 0 52 29"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M49.0003 0.75H3.00024C1.7576 0.75 0.750244 1.75736 0.750244 3V26C0.750244 27.2426 1.7576 28.25 3.00024 28.25H49.0003C50.2429 28.25 51.2503 27.2426 51.2503 26V3C51.2503 1.75736 50.2429 0.75 49.0003 0.75Z"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <path
                        d="M36.0001 19.25H44.0001"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <path
                        d="M30.0002 14.25H44.0002"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <path
                        d="M30.0002 9.25H44.0002"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <mask
                        id="mask0_50_4"
                        style="mask-type: luminance"
                        maskUnits="userSpaceOnUse"
                        x="6"
                        y="5"
                        width="18"
                        height="18"
                      >
                        <path
                          d="M24.0001 5H6.00006V23H24.0001V5Z"
                          fill="white"
                        />
                      </mask>
                      <g mask="url(#mask0_50_4)">
                        <path
                          d="M15.0001 13.558C16.9841 13.558 18.5921 11.944 18.5921 9.95398C18.5921 7.96298 16.9841 6.34998 15.0001 6.34998C13.0161 6.34998 11.4081 7.96298 11.4081 9.95398C11.4081 11.944 13.0161 13.558 15.0001 13.558Z"
                          stroke="black"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                        <path
                          d="M7.37305 21.643H22.6271ZM7.37305 21.643C7.35805 21.448 7.35004 21.253 7.35004 21.058C7.35004 19.069 8.15606 17.161 9.59106 15.755C11.0251 14.348 12.9711 13.558 15.0001 13.558C16.0051 13.558 16.999 13.752 17.928 14.129C18.856 14.506 19.6991 15.058 20.4091 15.755C21.1201 16.451 21.6831 17.278 22.0681 18.188C22.4521 19.098 22.6501 20.073 22.6501 21.058C22.6501 21.253 22.6421 21.449 22.6271 21.643"
                          stroke="black"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </g>
                    </svg>
                    <span class="upload-title">Upload front</span>
                    <span class="upload-desc">JPEG or PNG only</span>
                    <button class="btn btn-warning text-white upload-btn">
                      Select Files
                    </button>
                  </div>
                </div>
                <div class="col-6">
                  <div class="upload-box">
                    <svg
                      width="52"
                      height="29"
                      viewBox="0 0 52 29"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M48.9999 0.75H2.99988C1.75724 0.75 0.749878 1.75736 0.749878 3V26C0.749878 27.2426 1.75724 28.25 2.99988 28.25H48.9999C50.2425 28.25 51.2499 27.2426 51.2499 26V3C51.2499 1.75736 50.2425 0.75 48.9999 0.75Z"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <path
                        d="M28.0001 12.25H42.0001"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <path
                        d="M10.0005 19.25H42.0005"
                        stroke="black"
                        stroke-width="1.5"
                      />
                      <path
                        d="M20 14C21.1046 14 22 13.1046 22 12C22 10.8954 21.1046 10 20 10C18.8954 10 18 10.8954 18 12C18 13.1046 18.8954 14 20 14Z"
                        fill="black"
                      />
                      <path
                        d="M12.0005 14C13.1051 14 14.0005 13.1046 14.0005 12C14.0005 10.8954 13.1051 10 12.0005 10C10.8959 10 10.0005 10.8954 10.0005 12C10.0005 13.1046 10.8959 14 12.0005 14Z"
                        fill="black"
                      />
                    </svg>

                    <span class="upload-title">Upload back</span>
                    <span class="upload-desc">JPEG or PNG only</span>
                    <button class="btn btn-warning text-white upload-btn">
                      Select Files
                    </button>
                  </div>
                </div>
              </div>
              <div class="row selfie-container">
                <span class="inner-title"
                  >Take a photo of yourself with your ID
                  <a href="#">
                    <svg
                      width="15"
                      height="15"
                      viewBox="0 0 15 15"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <mask
                        id="mask0_1_146"
                        style="mask-type: luminance"
                        maskUnits="userSpaceOnUse"
                        x="0"
                        y="0"
                        width="16"
                        height="15"
                      >
                        <path
                          d="M15.0001 0H0.00012207V15H15.0001V0Z"
                          fill="white"
                        />
                      </mask>
                      <g mask="url(#mask0_1_146)">
                        <path
                          d="M15.0001 7.5C15.0001 9.489 14.2101 11.397 12.8031 12.803C11.3971 14.21 9.48912 15 7.50012 15C5.51112 15 3.60314 14.21 2.19714 12.803C0.790144 11.397 0.00012207 9.489 0.00012207 7.5C0.00012207 5.511 0.790144 3.60299 2.19714 2.19699C3.60314 0.789991 5.51112 0 7.50012 0C9.48912 0 11.3971 0.789991 12.8031 2.19699C14.2101 3.60299 15.0001 5.511 15.0001 7.5ZM5.1521 5.65601H5.92615C6.05515 5.65601 6.15811 5.55 6.17511 5.422C6.26011 4.807 6.68211 4.358 7.43311 4.358C8.07711 4.358 8.6651 4.68 8.6651 5.453C8.6651 6.049 8.31511 6.32301 7.76111 6.73901C7.13011 7.19701 6.63014 7.73299 6.66614 8.60199L6.66815 8.80499C6.66915 8.86699 6.6951 8.92499 6.7381 8.96799C6.7821 9.01099 6.84114 9.03601 6.90314 9.03601H7.66315C7.72515 9.03601 7.7851 9.01101 7.8291 8.96701C7.8731 8.92301 7.89813 8.863 7.89813 8.80099V8.703C7.89813 8.03 8.15312 7.834 8.84412 7.31C9.41512 6.876 10.0111 6.39399 10.0111 5.38199C10.0111 3.96599 8.81413 3.28101 7.50513 3.28101C6.31713 3.28101 5.01612 3.83401 4.92712 5.42401C4.92512 5.45501 4.9301 5.485 4.9411 5.513C4.9521 5.541 4.96811 5.56699 4.99011 5.58899C5.01111 5.61099 5.03615 5.62801 5.06415 5.63901C5.09215 5.65101 5.1221 5.65601 5.1521 5.65601ZM7.33209 11.696C7.90409 11.696 8.29712 11.327 8.29712 10.827C8.29712 10.31 7.90309 9.94601 7.33209 9.94601C6.78509 9.94601 6.38611 10.31 6.38611 10.827C6.38611 11.327 6.78513 11.696 7.33313 11.696H7.33209Z"
                          fill="#888888"
                        />
                      </g>
                    </svg> </a
                ></span>
                <div class="col-12">
                  <div class="upload-box">
                    <svg
                      width="50"
                      height="50"
                      viewBox="0 0 50 50"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <mask
                        id="mask0_1_94"
                        style="mask-type: luminance"
                        maskUnits="userSpaceOnUse"
                        x="0"
                        y="0"
                        width="51"
                        height="50"
                      >
                        <path
                          d="M50.0002 0H0.000183105V50H50.0002V0Z"
                          fill="white"
                        />
                      </mask>
                      <g mask="url(#mask0_1_94)">
                        <path
                          d="M16.8002 16.016L25.0001 7.81201L33.2001 16.016"
                          stroke="black"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                        <path
                          d="M25.0002 34.692V7.81201"
                          stroke="black"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                        <path
                          d="M42.1897 29.688V40.188C42.1897 40.585 42.0198 40.967 41.7298 41.248C41.4398 41.529 41.0398 41.688 40.6198 41.688H9.37976C8.95976 41.688 8.55978 41.529 8.26978 41.248C7.97978 40.967 7.80981 40.585 7.80981 40.188V29.688"
                          stroke="black"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </g>
                    </svg>
                    <span class="upload-title">Upload picture</span>
                    <span class="upload-desc">JPEG or PNG only</span>
                    <button class="btn btn-warning text-white upload-btn">
                      Select Files
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container socials">
      <span>Social Media</span>
      <div class="row social">
        <div class="col-12 col-sm-6 col-md-6 col-lg-3 youtube-container">
          <div class="youtube-inner-container">
            <div class="form-check form-switch social-switch">
              <input class="form-check-input" type="checkbox" checked />
            </div>
            <div class="social-title-container">
              <svg
                width="30"
                height="30"
                viewBox="0 0 30 30"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <mask
                  id="mask0_1_77"
                  style="mask-type: luminance"
                  maskUnits="userSpaceOnUse"
                  x="0"
                  y="0"
                  width="31"
                  height="30"
                >
                  <path
                    d="M30.0001 15C30.0001 6.71573 23.2844 0 15.0001 0C6.71585 0 0.00012207 6.71573 0.00012207 15C0.00012207 23.2843 6.71585 30 15.0001 30C23.2844 30 30.0001 23.2843 30.0001 15Z"
                    fill="white"
                  />
                </mask>
                <g mask="url(#mask0_1_77)">
                  <path
                    d="M15.0001 30C6.71712 30 0.00012207 23.28 0.00012207 15C0.00012207 6.72 6.71712 0 15.0001 0C23.2831 0 30.0001 6.72 30.0001 15C30.0001 23.28 23.2831 30 15.0001 30Z"
                    fill="#FF0000"
                  />
                  <path
                    d="M24.5464 10.17C24.3184 9.31004 23.6434 8.63002 22.7854 8.40002C21.2314 7.98002 15.0034 7.97998 15.0034 7.97998C15.0034 7.97998 8.77241 7.98002 7.22141 8.40002C6.36341 8.63002 5.68839 9.31004 5.46039 10.17C5.04039 11.74 5.04041 15 5.04041 15C5.04041 15 5.0404 18.26 5.4574 19.83C5.6854 20.69 6.36038 21.37 7.21838 21.6C8.77239 22.02 15.0004 22.02 15.0004 22.02C15.0004 22.02 21.2314 22.02 22.7824 21.6C23.6404 21.37 24.3154 20.69 24.5434 19.83C24.9604 18.26 24.9604 15 24.9604 15C24.9604 15 24.9604 11.74 24.5464 10.17ZM12.9634 17.96V12.04L18.1684 15L12.9634 17.96Z"
                    fill="white"
                  />
                </g>
              </svg>
              <span>@myChannel</span>
            </div>
            <hr />
            <div class="d-grid">
              <button class="btn btn-warning text-white upload-btn">
                Save
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-6 col-lg-3 facebook-container">
          <div class="facebook-inner-container">
            <div class="form-check form-switch social-switch">
              <input class="form-check-input" type="checkbox" />
            </div>
            <div class="social-title-container">
              <svg
                width="30"
                height="30"
                viewBox="0 0 30 30"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <mask
                  id="mask0_1_64"
                  style="mask-type: luminance"
                  maskUnits="userSpaceOnUse"
                  x="0"
                  y="0"
                  width="31"
                  height="30"
                >
                  <path d="M30.0002 0H0.000244141V30H30.0002V0Z" fill="white" />
                </mask>
                <g mask="url(#mask0_1_64)">
                  <path
                    d="M15.0002 30C23.2842 30 30.0002 23.28 30.0002 15C30.0002 6.72 23.2842 0 15.0002 0C6.71624 0 0.000244141 6.72 0.000244141 15C0.000244141 23.28 6.71624 30 15.0002 30Z"
                    fill="#888888"
                  />
                  <path
                    d="M17.6719 8.85999C18.5859 8.85999 19.799 8.85999 19.799 8.85999V5.68005C19.799 5.68005 18.5209 5.68005 16.7869 5.68005C15.0529 5.68005 12.7969 6.80003 12.7969 10.03C12.7969 10.63 12.7969 11.52 12.7969 12.55H9.91992V15.84H12.7969C12.7969 19.93 12.7969 24.39 12.7969 24.39H14.0739H15.088H16.2299C16.2299 24.39 16.2299 19.78 16.2299 15.84H19.09L19.564 12.55H16.2299C16.2299 11.47 16.2299 10.69 16.2299 10.46C16.2299 9.37996 16.7579 8.85999 17.6719 8.85999Z"
                    fill="white"
                  />
                </g>
              </svg>
              <span>@myChannel</span>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-6 col-lg-3 instagram-container">
          <div class="instagram-inner-container">
            <div class="form-check form-switch social-switch">
              <input class="form-check-input" type="checkbox" checked />
            </div>
            <div class="social-title-container">
              <svg
                width="30"
                height="30"
                viewBox="0 0 30 30"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <mask
                  id="mask0_1_51"
                  style="mask-type: luminance"
                  maskUnits="userSpaceOnUse"
                  x="-1"
                  y="0"
                  width="31"
                  height="30"
                >
                  <path
                    d="M29.9998 15C29.9998 6.71573 23.284 0 14.9998 0C6.71549 0 -0.000244141 6.71573 -0.000244141 15C-0.000244141 23.2843 6.71549 30 14.9998 30C23.284 30 29.9998 23.2843 29.9998 15Z"
                    fill="white"
                  />
                </mask>
                <g mask="url(#mask0_1_51)">
                  <path
                    d="M14.9998 30C6.71676 30 -0.000244141 23.28 -0.000244141 15C-0.000244141 6.72 6.71676 0 14.9998 0C23.2828 0 29.9998 6.72 29.9998 15C29.9998 23.28 23.2828 30 14.9998 30Z"
                    fill="url(#paint0_linear_1_51)"
                  />
                  <path
                    d="M15.0003 6.60999C17.7333 6.60999 18.0573 6.61004 19.1373 6.67004C20.1363 6.71004 20.6793 6.88002 21.0393 7.02002C21.5163 7.21002 21.8583 7.43003 22.2153 7.78003C22.5723 8.14003 22.7943 8.47996 22.9803 8.95996C23.1213 9.31996 23.2863 9.85999 23.3343 10.86C23.3823 11.94 23.3943 12.27 23.3943 15C23.3943 17.73 23.3853 18.06 23.3343 19.14C23.2893 20.14 23.1213 20.68 22.9803 21.04C22.7943 21.52 22.5723 21.86 22.2153 22.21C21.8583 22.57 21.5163 22.79 21.0393 22.98C20.6793 23.12 20.1363 23.29 19.1373 23.33C18.0573 23.38 17.7333 23.39 15.0003 23.39C12.2673 23.39 11.9433 23.38 10.8633 23.33C9.86428 23.29 9.3213 23.12 8.9613 22.98C8.4843 22.79 8.14228 22.57 7.78528 22.21C7.42828 21.86 7.20633 21.52 7.02033 21.04C6.87933 20.68 6.71432 20.14 6.66632 19.14C6.61832 18.06 6.60632 17.73 6.60632 15C6.60632 12.27 6.61532 11.94 6.66632 10.86C6.71132 9.85999 6.87933 9.31996 7.02033 8.95996C7.20633 8.47996 7.42828 8.14003 7.78528 7.78003C8.14228 7.43003 8.4843 7.21002 8.9613 7.02002C9.3213 6.88002 9.86428 6.71004 10.8633 6.67004C11.9433 6.61004 12.2673 6.60999 15.0003 6.60999ZM15.0003 4.76001C12.2193 4.76001 11.8713 4.76995 10.7793 4.81995C9.6903 4.86995 8.9463 5.05005 8.2923 5.30005C7.6203 5.56005 7.04729 5.90998 6.48029 6.47998C5.91029 7.04998 5.56228 7.62004 5.29828 8.29004C5.04628 8.95004 4.87229 9.69003 4.82129 10.78C4.77029 11.87 4.7583 12.22 4.7583 15C4.7583 17.78 4.77029 18.13 4.82129 19.22C4.87229 20.31 5.04328 21.06 5.29828 21.71C5.55928 22.38 5.91029 22.95 6.48029 23.52C7.05029 24.09 7.62029 24.44 8.29529 24.7C8.94629 24.95 9.69029 25.1301 10.7823 25.1801C11.8743 25.2301 12.2223 25.24 15.0033 25.24C17.7843 25.24 18.1323 25.2301 19.2243 25.1801C20.3133 25.1301 21.0573 24.96 21.7113 24.7C22.3803 24.44 22.9533 24.09 23.5203 23.52C24.0903 22.95 24.4383 22.38 24.7023 21.7C24.9543 21.05 25.1283 20.31 25.1793 19.22C25.2303 18.13 25.2423 17.78 25.2423 15C25.2423 12.22 25.2303 11.87 25.1793 10.78C25.1283 9.69003 24.9573 8.94004 24.7023 8.29004C24.4413 7.62004 24.0903 7.04998 23.5203 6.47998C22.9503 5.90998 22.3803 5.56005 21.7053 5.30005C21.0543 5.05005 20.3103 4.86995 19.2183 4.81995C18.1293 4.76995 17.7813 4.76001 15.0003 4.76001Z"
                    fill="white"
                  />
                  <path
                    d="M15.0003 9.73999C12.0963 9.73999 9.74133 12.1 9.74133 15C9.74133 17.9 12.0963 20.26 15.0003 20.26C17.9043 20.26 20.2593 17.9 20.2593 15C20.2593 12.1 17.9043 9.73999 15.0003 9.73999ZM15.0003 18.41C13.1163 18.41 11.5863 16.89 11.5863 15C11.5863 13.11 13.1163 11.59 15.0003 11.59C16.8843 11.59 18.4143 13.11 18.4143 15C18.4143 16.89 16.8843 18.41 15.0003 18.41Z"
                    fill="white"
                  />
                  <path
                    d="M20.4659 10.76C21.1449 10.76 21.6959 10.21 21.6959 9.53003C21.6959 8.85003 21.1449 8.30005 20.4659 8.30005C19.7869 8.30005 19.236 8.85003 19.236 9.53003C19.236 10.21 19.7869 10.76 20.4659 10.76Z"
                    fill="white"
                  />
                </g>
                <defs>
                  <linearGradient
                    id="paint0_linear_1_51"
                    x1="4.39276"
                    y1="25.61"
                    x2="25.6068"
                    y2="4.39"
                    gradientUnits="userSpaceOnUse"
                  >
                    <stop stop-color="#FFD521" />
                    <stop offset="0.0551048" stop-color="#FFD020" />
                    <stop offset="0.1241" stop-color="#FEC01E" />
                    <stop offset="0.2004" stop-color="#FCA71B" />
                    <stop offset="0.2821" stop-color="#FA8316" />
                    <stop offset="0.3681" stop-color="#F85510" />
                    <stop offset="0.4563" stop-color="#F51E09" />
                    <stop offset="0.5" stop-color="#F30005" />
                    <stop offset="0.5035" stop-color="#F20007" />
                    <stop offset="0.5966" stop-color="#E1003B" />
                    <stop offset="0.6879" stop-color="#D30067" />
                    <stop offset="0.7757" stop-color="#C70088" />
                    <stop offset="0.8589" stop-color="#BF00A0" />
                    <stop offset="0.9357" stop-color="#BB00AF" />
                    <stop offset="1" stop-color="#B900B4" />
                  </linearGradient>
                </defs>
              </svg>
              <span>@myChannel</span>
            </div>
            <hr />
            <div class="d-grid">
              <button class="btn btn-warning text-white upload-btn">
                Save
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-6 col-lg-3 tiktok-container">
          <div class="tiktok-inner-container">
            <div class="form-check form-switch social-switch">
              <input class="form-check-input" type="checkbox" checked />
            </div>
            <div class="social-title-container">
              <svg
                width="30"
                height="30"
                viewBox="0 0 30 30"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <mask
                  id="mask0_1_38"
                  style="mask-type: luminance"
                  maskUnits="userSpaceOnUse"
                  x="0"
                  y="0"
                  width="31"
                  height="30"
                >
                  <path
                    d="M30.0002 15C30.0002 6.71573 23.2845 0 15.0002 0C6.71597 0 0.000244141 6.71573 0.000244141 15C0.000244141 23.2843 6.71597 30 15.0002 30C23.2845 30 30.0002 23.2843 30.0002 15Z"
                    fill="white"
                  />
                </mask>
                <g mask="url(#mask0_1_38)">
                  <path
                    fill-rule="evenodd"
                    clip-rule="evenodd"
                    d="M15.0002 0C23.2802 0 30.0002 6.72 30.0002 15C30.0002 23.28 23.2802 30 15.0002 30C6.72025 30 0.000244141 23.28 0.000244141 15C0.000244141 6.72 6.72025 0 15.0002 0ZM18.3702 6.20996C18.3702 6.47996 18.4503 10.36 22.5203 10.6C22.5203 11.72 22.5203 12.53 22.5203 13.6C22.2103 13.62 19.8402 13.45 18.3602 12.13V17.97C18.4202 22.02 15.4303 24.49 11.5403 23.63C4.81028 21.62 7.05029 11.66 13.8003 12.72C13.8003 15.94 13.8003 12.7199 13.8003 15.9399C11.0103 15.5299 10.0802 17.85 10.8202 19.51C11.4902 21.02 14.2702 21.35 15.2402 19.22C15.3502 18.8 15.4003 18.32 15.4003 17.79V6.19995L18.3702 6.20996Z"
                    fill="black"
                  />
                </g>
              </svg>
              <span>@myChannel</span>
            </div>
            <hr />
            <div class="d-grid">
              <button class="btn btn-warning text-white upload-btn">
                Save
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container sponsors">
      <span>Sponsor Coverage</span>
      <p>Base on his total Subscribers/Followers</p>
      <p>spread over the platform.</p>
      <div class="row sponsors-progress">
        <div class="col-12 col-sm-12 col-md-12 col-lg-6">
          <ul>
            <li>
              <div class="youtube-progress-container">
                <span>Youtube</span>
                <span>63%</span>
              </div>
              <div class="progress">
                <div
                  class="progress-bar"
                  style="width: 63%"
                  role="progressbar"
                  aria-valuenow="63"
                  aria-valuemin="0"
                  aria-valuemax="100"
                ></div>
              </div>
            </li>
            <li>
              <div class="facebook-progress-container">
                <span>Facebook</span>
                <span>46%</span>
              </div>
              <div class="progress">
                <div
                  class="progress-bar"
                  style="width: 46%"
                  role="progressbar"
                  aria-valuenow="46"
                  aria-valuemin="0"
                  aria-valuemax="100"
                ></div>
              </div>
            </li>
            <li>
              <div class="instagram-progress-container">
                <span>instagram</span>
                <span>71%</span>
              </div>
              <div class="progress">
                <div
                  class="progress-bar"
                  style="width: 71%"
                  role="progressbar"
                  aria-valuenow="71"
                  aria-valuemin="0"
                  aria-valuemax="100"
                ></div>
              </div>
            </li>
            <li>
              <div class="tiktok-progress-container">
                <span>Tiktok</span>
                <span>27%</span>
              </div>
              <div class="progress">
                <div
                  class="progress-bar"
                  style="width: 27%"
                  role="progressbar"
                  aria-valuenow="27"
                  aria-valuemin="0"
                  aria-valuemax="100"
                ></div>
              </div>
            </li>
            <li>
              <div class="label-progress-container">
                <span>Label</span>
                <span>13%</span>
              </div>
              <div class="progress">
                <div
                  class="progress-bar"
                  style="width: 13%"
                  role="progressbar"
                  aria-valuenow="13"
                  aria-valuemin="0"
                  aria-valuemax="100"
                ></div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="container save-profile">
      <button class="btn btn-warning text-white upload-btn">
        Save &amp; Synchronize
      </button>
    </div>
    <div class="container-fluid footer">
      <div class="container footer-inner">
        <div class="row">
          <div class="col-12 col-sm-12 col-md-12 col-lg-4 footer-left">
            <span>&copy; 2023 - All rights reserved</span>
          </div>
          <div class="col-12 col-sm-12 col-md-12 col-lg-8 footer-right">
            <ul>
              <li><a href="#">Compensation Calculator</a></li>
              <li><a href="#">Affiliates</a></li>
              <li><a href="#">Contact Us</a></li>
              <li><a href="#">Support</a></li>
              <li><a href="#">Our Partners</a></li>
              <li><a href="#">Team</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
