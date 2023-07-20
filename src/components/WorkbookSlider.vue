<script setup></script>

<template>
  <div class="flex justify-center">
    <div class="w-full mt-[50px]">
      <div class="text-[#464A50] font-bold text-[16px] ml-[20px]">Recent workbooks</div>
      <div className="lg:flex justify-center">
        <div
          className="flex overflow-scroll ml-5 mt-[50px] scrollbar-hide no-scrollbar w-full max-w-7xl"
        >
          <div class="relative">
            <div
              class="w-full max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 pl-[15px]"
            >
              <div class="flex justify-end px-4 pt-[10px]">
                <button
                  id="dropdownButton"
                  data-dropdown-toggle="dropdown"
                  class="inline-block text-[#34E5F9] dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-sm p-1.5"
                  type="button"
                >
                  <span class="sr-only">Open dropdown</span>
                  <svg
                    class="w-5 h-5"
                    aria-hidden="true"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 16 3"
                  >
                    <path
                      d="M2 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm6.041 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3ZM14 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z"
                    />
                  </svg>
                </button>
                <!-- Dropdown menu -->
                <div
                  id="dropdown"
                  class="z-10 hidden text-base list-none bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700"
                >
                  <ul class="py-2" aria-labelledby="dropdownButton">
                    <li>
                      <a
                        href="#"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"
                        >Edit</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"
                        >Export Data</a
                      >
                    </li>
                  </ul>
                </div>
              </div>
              <div class="flex items-center pb-[20px]">
                <div
                  class="bg-[#FFECEA] w-[100px] h-[100px] rounded-[10px] flex justify-center items-center"
                >
                  <img src="/images/package.png" class="w-[30px] h-[30px]" alt="icon" />
                </div>
                <div class="pl-[10px]">
                  <div class="font-bold text-[#464A50]">UX Research</div>
                  <div class="text-[#464A50] text-[14px] mt-[5px]">25 questions</div>
                  <div class="text-[#464A50] text-[14px] mt-[5px]">30 minutes</div>
                </div>
              </div>
              <div class="text-[#464A50] text-[14px]">
                contsins questions that will help improve your design thinking process to enhance
                your UX design
              </div>
              <hr class="mt-[10px] mb-[10px] w-[93%]" />
              <!-- <div> -->

              <div class="flex mb-5 -space-x-4">
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <a
                  class="flex items-center justify-center px-[10px] h-10 text-xs font-medium text-[#464A50] bg-[#F0F4FA] border-2 border-white rounded-full hover:bg-gray-600 dark:border-gray-800"
                  href="#"
                  >+120 results</a
                >
              </div>

              <!-- </div> -->
            </div>
          </div>
          <div class="relative">
            <div
              class="w-full max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 pl-[15px]"
            >
              <div class="flex justify-end px-4 pt-[10px]">
                <button
                  id="dropdownButton"
                  data-dropdown-toggle="dropdown"
                  class="inline-block text-[#34E5F9] dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-sm p-1.5"
                  type="button"
                >
                  <span class="sr-only">Open dropdown</span>
                  <svg
                    class="w-5 h-5"
                    aria-hidden="true"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 16 3"
                  >
                    <path
                      d="M2 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm6.041 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3ZM14 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z"
                    />
                  </svg>
                </button>
                <!-- Dropdown menu -->
                <div
                  id="dropdown"
                  class="z-10 hidden text-base list-none bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700"
                >
                  <ul class="py-2" aria-labelledby="dropdownButton">
                    <li>
                      <a
                        href="#"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"
                        >Edit</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"
                        >Export Data</a
                      >
                    </li>
                  </ul>
                </div>
              </div>
              <div class="flex items-center pb-[20px]">
                <div
                  class="bg-[#FFECEA] w-[100px] h-[100px] rounded-[10px] flex justify-center items-center"
                >
                  <img src="/images/package.png" class="w-[30px] h-[30px]" alt="icon" />
                </div>
                <div class="pl-[10px]">
                  <div class="font-bold text-[#464A50]">UX Research</div>
                  <div class="text-[#464A50] text-[14px] mt-[5px]">25 questions</div>
                  <div class="text-[#464A50] text-[14px] mt-[5px]">30 minutes</div>
                </div>
              </div>
              <div class="text-[#464A50] text-[14px]">
                contsins questions that will help improve your design thinking process to enhance
                your UX design
              </div>
              <hr class="mt-[10px] mb-[10px] w-[93%]" />
              <!-- <div> -->

              <div class="flex mb-5 -space-x-4">
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <a
                  class="flex items-center justify-center px-[10px] h-10 text-xs font-medium text-[#464A50] bg-[#F0F4FA] border-2 border-white rounded-full hover:bg-gray-600 dark:border-gray-800"
                  href="#"
                  >+120 results</a
                >
              </div>

              <!-- </div> -->
            </div>
          </div>
          <div class="relative">
            <div
              class="w-full max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 pl-[15px]"
            >
              <div class="flex justify-end px-4 pt-[10px]">
                <button
                  id="dropdownButton"
                  data-dropdown-toggle="dropdown"
                  class="inline-block text-[#34E5F9] dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-sm p-1.5"
                  type="button"
                >
                  <span class="sr-only">Open dropdown</span>
                  <svg
                    class="w-5 h-5"
                    aria-hidden="true"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 16 3"
                  >
                    <path
                      d="M2 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm6.041 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3ZM14 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z"
                    />
                  </svg>
                </button>
                <!-- Dropdown menu -->
                <div
                  id="dropdown"
                  class="z-10 hidden text-base list-none bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700"
                >
                  <ul class="py-2" aria-labelledby="dropdownButton">
                    <li>
                      <a
                        href="#"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"
                        >Edit</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"
                        >Export Data</a
                      >
                    </li>
                  </ul>
                </div>
              </div>
              <div class="flex items-center pb-[20px]">
                <div
                  class="bg-[#FFECEA] w-[100px] h-[100px] rounded-[10px] flex justify-center items-center"
                >
                  <img src="/images/package.png" class="w-[30px] h-[30px]" alt="icon" />
                </div>
                <div class="pl-[10px]">
                  <div class="font-bold text-[#464A50]">UX Research</div>
                  <div class="text-[#464A50] text-[14px] mt-[5px]">25 questions</div>
                  <div class="text-[#464A50] text-[14px] mt-[5px]">30 minutes</div>
                </div>
              </div>
              <div class="text-[#464A50] text-[14px]">
                contsins questions that will help improve your design thinking process to enhance
                your UX design
              </div>
              <hr class="mt-[10px] mb-[10px] w-[93%]" />
              <!-- <div> -->

              <div class="flex mb-5 -space-x-4">
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <img
                  class="w-10 h-10 border-2 border-white rounded-full dark:border-gray-800"
                  src="/images/avatar.jpeg"
                  alt=""
                />
                <a
                  class="flex items-center justify-center px-[10px] h-10 text-xs font-medium text-[#464A50] bg-[#F0F4FA] border-2 border-white rounded-full hover:bg-gray-600 dark:border-gray-800"
                  href="#"
                  >+120 results</a
                >
              </div>

              <!-- </div> -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<!-- <div className="lg:flex justify-center">
    <div className="flex overflow-scroll ml-5 mt-[50px] scrollbar-hide no-scrollbar w-full max-w-7xl">
      <div className="relative h-96 min-w-[300px]">
        <Image
          src="/img1.svg"
          fill={true}
          alt="Image"
          style={{ objectFit: "cover" }}
          className="rounded-2xl"
        />
      </div>
      <div className="relative h-96 min-w-[300px]">
        <Image
          src={imgboy}
          fill={true}
          alt="Image"
          style={{ objectFit: "cover" }}
          className="rounded-2xl"
        />
      </div>
      <div className="relative h-96 min-w-[300px]">
        <Image
          src={imgirl}
          fill={true}
          alt="Image"
          style={{ objectFit: "cover" }}
          className="rounded-2xl"
        />
      </div>
      <div className="relative h-96 min-w-[300px]">
        <Image
          src="/img1.svg"
          fill={true}
          alt="Image"
          style={{ objectFit: "cover" }}
          className="rounded-2xl"
        />
      </div>
      <div className="relative h-96 min-w-[300px]">
        <Image
          src="/img1.svg"
          fill={true}
          alt="Image"
          style={{ objectFit: "cover" }}
          className="rounded-2xl"
        />
      </div>
      <div className="relative h-96 min-w-[300px]">
        <Image
          src="/img1.svg"
          fill={true}
          alt="Image"
          style={{ objectFit: "cover" }}
          className="rounded-2xl"
        />
      </div>
    </div>
  </div> -->
