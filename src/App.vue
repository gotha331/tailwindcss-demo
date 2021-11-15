<template>
  <div class="text-sm text-gray-900">
    <nav class="flex items-center px-4 py-3 bg-gray-900 justify-between">
      <div class="text-white flex items-center space-x-4">
        <a class="w-6 fill-current hover:text-gray-200" href="#">
          <svg
            class="w-6"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            />
          </svg>
        </a>

        <div class="hidden lg:block relative">
          <input
            type="text"
            class="rounded bg-gray-900 border border-gray-600 placeholder-gray-400 w-72 px-3 py-1"
            placeholder="Search or jump to ..."
          />
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div class="border border-gray-600 rounded text-xs text-gray-400 px-2 mr-2">/</div>
          </div>
        </div>

        <ul class="hidden lg:flex item-center font-semibold space-x-4">
          <li>
            <a href="#" class="hover:text-gray-400">Pull requests</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-400">Issue</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-400">Marketplace</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-400">Explore</a>
          </li>
        </ul>
      </div>
      <div class="text-white flex items-center space-x-4">
        <a href="#" class="hidden lg:block relative hover:text-gray-400">
          <svg
            class="w-5 fill-current"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              d="M8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"
            />
            <path
              fill-rule="evenodd"
              d="M8 1.5A3.5 3.5 0 004.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01l.001.006c0 .002.002.004.004.006a.017.017 0 00.006.004l.007.001h10.964l.007-.001a.016.016 0 00.006-.004.016.016 0 00.004-.006l.001-.007a.017.017 0 00-.003-.01l-1.703-2.554a1.75 1.75 0 01-.294-.97V5A3.5 3.5 0 008 1.5zM3 5a5 5 0 0110 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.518 1.518 0 0113.482 13H2.518a1.518 1.518 0 01-1.263-2.36l1.703-2.554A.25.25 0 003 7.947V5z"
            />
          </svg>
          <div class="bg-blue-400 rounded-full w-2 h-2 absolute top-0 right-0"></div>
        </a>
        <a href="#" class="hidden lg:flex items-center hover:text-gray-400">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M10 3a1 1 0 011 1v5h5a1 1 0 110 2h-5v5a1 1 0 11-2 0v-5H4a1 1 0 110-2h5V4a1 1 0 011-1z"
              clip-rule="evenodd"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-3 w-3"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </a>
        <a href="#" class="flex items-center hover:text-gray-400">
          <div class="w-6 h-6 rounded-full bg-blue-600"></div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-3 w-3"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </a>
      </div>
    </nav>

    <div
      class="repo-stats bg-gray-100 flex flex-col lg:flex-row item-center justify-between px-8 py-4"
    >
      <div class="flex items-center">
        <svg
          class="w-4 fill-current text-gray-600"
          aria-hidden="true"
          viewBox="0 0 16 16"
          version="1.1"
          data-view-component="true"
        >
          <path
            fill-rule="evenodd"
            d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"
          />
        </svg>

        <div class="flex item-center text-xl ml-2">
          <a href="#" class="text-blue-600 hover:underline">tailwindcss</a>
          <span class="mx-1">/</span>
          <a href="#" class="text-blue-600 hover:underline font-semibold">tailwindcss</a>
        </div>

        <div
          class="flex items-center p-2 h-4 bg-gray-100 rounded-xl border border-gray-300 text-gray-600 text-xs ml-2"
        >Public</div>
      </div>

      <div class="flex space-x-2 mt-4 lg:mt-0">
        <div class="flex text-xs shadow-sm h-7">
          <button
            class="border border-gray-300 rounded-lg rounded-r-none px-3 py-1 flex items-center space-x-2"
          >
            <svg
              class="w-4 h-4"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"
              />
            </svg>

            <span class="font-semibold">Watch</span>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-3 w-3"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                clip-rule="evenodd"
              />
            </svg>
          </button>
          <a
            href="#"
            class="flex items-center border border-gray-300 rounded-lg rounded-l-none px-3 py-1 border-l-0 font-semibold hover:text-blue-400 bg-white"
          >548</a>
        </div>

        <div class="flex text-xs shadow-sm h-7">
          <button
            class="border border-gray-300 rounded-lg rounded-r-none px-3 py-1 flex items-center space-x-2"
          >
            <svg
              class="w-4 h-4"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"
              />
            </svg>

            <span class="font-semibold">Star</span>
          </button>
          <a
            href="#"
            class="flex items-center border border-gray-300 rounded-lg rounded-l-none px-3 py-1 border-l-0 font-semibold hover:text-blue-400 bg-white"
          >47.9k</a>
        </div>

        <div class="flex text-xs shadow-sm h-7">
          <button
            class="border border-gray-300 rounded-lg rounded-r-none px-3 py-1 flex items-center space-x-2"
          >
            <svg
              class="w-4 h-4"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"
              />
            </svg>
            <span class="font-semibold">Fork</span>
          </button>
          <a
            href="#"
            class="flex items-center border border-gray-300 rounded-lg rounded-l-none px-3 py-1 border-l-0 font-semibold hover:text-blue-400 bg-white"
          >2.2k</a>
        </div>
      </div>
    </div>
    <!-- end repo stats -->

    <ul class="repo-nav bg-gray-100 border-b border-gray-300 flex items-center px-8 pt-4">
      <li class="font-semibold">
        <a href="#" class="flex items-center space-x-2 border-b-2 border-red-500 px-4 pb-3">
          <svg
            class="w-4 h-4"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              fill-rule="evenodd"
              d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"
            />
          </svg>
          <span>Code</span>
        </a>
      </li>

      <li class="font-semibold">
        <a
          href="#"
          class="flex items-center space-x-2 px-4 pb-3 text-gray-700 hover:border-gray-300 border-b"
        >
          <svg
            class="w-4 h-4 fill-current"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              fill-rule="evenodd"
              d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"
            />
          </svg>
          <span>Pull requests</span>
          <div class="flex items-center bg-gray-200 rounded-lg px-2 ml-2">38</div>
        </a>
      </li>

      <li class="font-semibold">
        <a
          href="#"
          class="flex items-center space-x-2 px-4 pb-3 text-gray-700 hover:border-gray-300 border-b"
        >
          <svg
            class="w-4 h-4 fill-current"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              fill-rule="evenodd"
              d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"
            />
          </svg>
          <span>Actions</span>
        </a>
      </li>

      <li class="font-semibold">
        <a
          href="#"
          class="flex items-center space-x-2 px-4 pb-3 text-gray-700 hover:border-gray-300 border-b"
        >
          <svg
            class="w-4 h-4 fill-current"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              fill-rule="evenodd"
              d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"
            />
          </svg>
          <span>Security</span>
        </a>
      </li>

      <li class="font-semibold">
        <a
          href="#"
          class="flex items-center space-x-2 px-4 pb-3 text-gray-700 hover:border-gray-300 border-b"
        >
          <svg
            class="w-4 h-4 fill-current"
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
          >
            <path
              fill-rule="evenodd"
              d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"
            />
          </svg>
          <span>Insights</span>
        </a>
      </li>
    </ul>
    <!-- end repo nav -->

    <div class="container mx-auto my-8 px-4 flex flex-col lg:flex-row">
      <div class="file-explorer-container w-full lg:w-3/4 mr-8">
        <div class="branch-navigation flex items-center justify-between">
          <div class="flex items-center space-x-1">
            <button
              class="border border-gray-300 bg-gray-100 rounded-md px-4 py-1 hover:bg-gray-200 flex items-center space-x-2"
            >
              <svg
                class="w-4 h-4 fill-current"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                />
              </svg>
              <span>master</span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-3 w-3"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </button>
            <a href="#" class="px-4 py-1 hover:text-blue-400 flex items-center space-x-1">
              <svg
                class="w-4 h-4 fill-current"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                />
              </svg>
              <span>45 branches</span>
            </a>

            <a href="#" class="px-4 py-1 hover:text-blue-400 flex items-center space-x-1">
              <svg
                class="w-4 h-4 fill-current"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
                />
              </svg>
              <span>181 tags</span>
            </a>
          </div>

          <div class="hidden lg:flex items center space-x-2">
            <button
              class="px-4 py-1 border border-gray-300 rounded bg-gray-100 hover:bg-gray-200"
            >Go to file</button>

            <button
              class="px-4 py-1 border border-gray-300 rounded bg-gray-100 hover:bg-gray-200 flex items-center"
            >
              Add file
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-3 w-3"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </button>

            <button
              class="px-4 py-1 border border-green-700 rounded bg-green-600 hover:bg-green-700 text-white flex items-center"
            >
              Code
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-3 w-3"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </button>
          </div>
        </div>
        <!-- end branch navigation -->
        <div
          class="commits-container bg-gray-100 rounded-md rounded-b-none border border-gray-300 border-b-0 flex items-center justify-between px-4 py-4 mt-5"
        >
          <div class="flex items-center space-x-2">
            <div class="w-6 h-6 rounded-full bg-blue-500"></div>
            <a href="#" class="font-semibold hover:underline">adamwathan</a>
            <a href="#" class="hover:underline hover:text-blue-500">
              Don't use pointer cursor on disabled buttons by default
              <span
                class="text-blue-500"
              >#5772</span>
            </a>
          </div>

          <div class="hidden lg:flex items-center">
            <svg
              class="w-4 h-4 text-green-400 fill-current"
              aria-label="6 / 6 checks OK"
              role="img"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"
              />
            </svg>
            <a href="#" class="hover:underline hover:text-blue-600 text-gray-600 ml-1">f2bc242</a>
            <a href="#" class="hover:underline hover:text-blue-600 text-gray-600 ml-1">yesterday</a>
            <a href="#" class="flex items-center space-x-1 hover:text-blue-600 cursor-pointer ml-3">
              <svg
                class="w-4 h-4 fill-current"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"
                />
              </svg>
              <span class="font-semibold">3894</span>
            </a>
            <span class="ml-1">commits</span>
          </div>
        </div>
        <!-- end commits container -->

        <div
          class="file-explorer rounded-md rounded-t-none border border-gray-300 divide-y divide-gray-300"
        >
          <div class="flex justify-between items-center px-4 py-2 hover:bg-gray-100">
            <div class="w-4/12 flex items-center">
              <svg
                class="w-4 h-4 fill-current text-blue-200"
                aria-label="Directory"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"
                />
              </svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">.github/workflows</a>
            </div>
            <div class="w-6/12 text-left truncate">
              <a
                href="#"
                class="hover:underline hover:text-blue-600"
              >Build: Made stack-protector guard use global addressing instead of TLS ...</a>
            </div>
            <div class="w-2/12 text-right">11 days ago</div>
          </div>
          <div class="flex justify-between items-center px-4 py-2 hover:bg-gray-100">
            <div class="w-4/12 flex items-center">
              <svg
                class="w-4 h-4 fill-current text-blue-200"
                aria-label="Directory"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"
                />
              </svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">AppleModels</a>
            </div>
            <div class="w-6/12 text-left">
              <a
                href="#"
                class="hover:underline hover:text-blue-600"
              >DataBase: Updated builtin firmware versions</a>
            </div>
            <div class="w-2/12 text-right">15 days ago</div>
          </div>
          <div class="flex justify-between items-center px-4 py-2 hover:bg-gray-100">
            <div class="w-4/12 flex items-center">
              <svg
                class="w-4 h-4 fill-current text-blue-200"
                aria-label="Directory"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"
                />
              </svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">Application</a>
            </div>
            <div class="w-6/12 text-left">
              <a
                href="#"
                class="hover:underline hover:text-blue-600"
              >Build: Fix minor typos, thx Slice&Co</a>
            </div>
            <div class="w-2/12 text-right">11 days ago</div>
          </div>
          <div class="flex justify-between items-center px-4 py-2 hover:bg-gray-100">
            <div class="w-4/12 flex items-center">
              <svg
                class="w-4 h-4 fill-current text-blue-200"
                aria-label="Directory"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"
                />
              </svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">Debug</a>
            </div>
            <div class="w-6/12 text-left">
              <a
                href="#"
                class="hover:underline hover:text-blue-600"
              >Debug: Add VSCode source-level debug example config; update QEMU FAT …</a>
            </div>
            <div class="w-2/12 text-right">5 months ago</div>
          </div>
          <div class="flex justify-between items-center px-4 py-2 hover:bg-gray-100">
            <div class="w-4/12 flex">
              <svg
                class="w-4 h-4 fill-current text-blue-200"
                aria-label="Directory"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"
                />
              </svg>
              <a href="#" class="hover:underline hover:text-blue-600 ml-3">Docs</a>
            </div>
            <div class="w-6/12 text-left">
              <a href="#" class="hover:underline hover:text-blue-600">Docs: Hide Auxiliary</a>
            </div>
            <div class="w-2/12 text-right">3 days ago</div>
          </div>
        </div>
      </div>
      <!-- end file explorer container -->

      <div class="sidebar w-full lg:w-1/4 mt-4 lg:mt-0 text-left">
        <div class="about">
          <h4 class="font-semibold">About</h4>
          <p class="mt-4 font-semibold">OpenCore bootloader</p>
          <div class="flex items-center space-x-2 mt-4 text-gray-500 hover:text-blue-600">
            <svg
              class="w-4 fill-current"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"
              />
            </svg>
            <a href="#">Readme</a>
          </div>
          <!-- end readme -->

          <div class="flex items-center space-x-2 mt-4 text-gray-500 hover:text-blue-600">
            <svg
              class="w-4 fill-current"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"
              />
            </svg>
            <a href="#">BSD-3-Clause License</a>
          </div>
          <!-- end license -->

          <div class="tags text-xs font-semibold flex flex-wrap items-center mt-2">
            <a
              href="#"
              class="bg-blue-100 hover:bg-blue-500 hover:text-white text-blue-600 rounded-full px-2 py-1 mt-2 mr-2"
            >OC</a>
            <a
              href="#"
              class="bg-blue-100 hover:bg-blue-500 hover:text-white text-blue-600 rounded-full px-2 py-1 mt-2 mr-2"
            >MacOS</a>
            <a
              href="#"
              class="bg-blue-100 hover:bg-blue-500 hover:text-white text-blue-600 rounded-full px-2 py-1 mt-2 mr-2"
            >KVM</a>
            <a
              href="#"
              class="bg-blue-100 hover:bg-blue-500 hover:text-white text-blue-600 rounded-full px-2 py-1 mt-2 mr-2"
            >Apple</a>
            <a
              href="#"
              class="bg-blue-100 hover:bg-blue-500 hover:text-white text-blue-600 rounded-full px-2 py-1 mt-2 mr-2"
            >Hackintosh</a>
          </div>
          <!-- end tags -->

          <a href="#" class="flex items-center space-x-2 mt-4 group">
            <svg
              class="w-4 fill-current group-hover:text-red-600"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"
              />
            </svg>
            <span class="group-hover:text-blue-600">Readme</span>
          </a>
        </div>
        <!-- end about -->
        <div class="releases border-t border-gray-300 mt-6 pt-6">
          <h4 class="font-semibold flex items-center">
            <span>Releases</span>
            <div class="text-xs rounded-lg bg-gray-100 text-gray-800 px-2 ml-1">163</div>
          </h4>
          <a href="#" class="flex items-start group mt-4">
            <svg
              class="w-4 mt-0.5 fill-current text-green-500 group-hover:text-blue-500"
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
            >
              <path
                fill-rule="evenodd"
                d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
              />
            </svg>
            <span class="ml-2">
              <span class="font-semibold group-hover:text-blue-600 mr-2">v0.7.5</span>
              <span
                class="text-xs border border-green-500 text-green-600 rounded-full font-semibold inline-block px-2"
              >Latest</span>
              <span class="text-xs block group-hover:text-blue-600">7 days ago</span>
            </span>

            <div class="mt-4">
              <a href="#" class="text-blue-400 hover:underline">+ 162 releases</a>
            </div>
          </a>
        </div>
        <!-- end releases -->

        <div class="packages border-t border-gray-300 mt-6 pt-6">
          <h4 class="font-semibold flex items-center">
            <span>Packages</span>
          </h4>

          <div class="mt-6">
            <span class="text-xs text-gray-600">No packages published</span>
          </div>
        </div>
        <!-- end packages -->

        <div class="used-by border-t border-gray-300 mt-6 pt-6">
          <h4 class="font-semibold flex items-center">
            <span>Used by</span>
            <div class="text-xs rounded-lg bg-gray-100 text-gray-800 px-2 ml-1">322k</div>
          </h4>

          <div class="flex items-center mt-4">
            <a href="#" class="inline-flex items-center group -space-x-2">
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
              <div class="w-7 h-7 rounded-full bg-blue-500 border-2 border-white"></div>
            </a>
            <span
              class="text-xs font-semibold text-blue-500 group-hover:underline ml-2 h-full"
            >+322,331</span>
          </div>
        </div>
        <!-- end used by -->

        <div class="contributors border-t border-gray-300 mt-6 pt-6">
          <h4 class="font-semibold flex items-center">
            <span>Contributors</span>
            <div class="text-xs rounded-lg bg-gray-100 text-gray-800 px-2 ml-1">64</div>
          </h4>
          <div class="mt-2 mb-2">
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
            <div class="w-9 h-9 inline-block rounded-full bg-blue-500 border-2 border-white"></div>
          </div>
          <span
            class="text-xs font-semibold text-blue-500 group-hover:underline ml-2 h-full"
          >+53 contributros</span>
        </div>
        <!-- end contributors -->

        <div class="languages border-t border-gray-300 mt-6 pt-6">
          <h4 class="font-semibold flex items-center">
            <span>Languages</span>
            <div class="text-xs rounded-lg bg-gray-100 text-gray-800 px-2 ml-1">64</div>
          </h4>
          <div class="mt-4 flex">
            <div class="w-8/12 h-2 rounded-md rounded-r-none bg-yellow-300"></div>
            <div class="w-3/12 h-2 bg-purple-300 border-white"></div>
            <div class="w-1/12 h-2 rounded-md bg-red-300 rounded-l-none border-white"></div>
          </div>
          <ul class="mt-2 flex flex-wrap space-y-1 items-center text-xs">
            <li class="flex items-center mr-8">
              <span class="w-2 h-2 rounded-full bg-yellow-300"></span>
              <span class="ml-4 mr-1 group cursor-pointer font-semibold">C</span>
              <span class="text-gray-500">95.4%</span>
            </li>
            <li class="flex items-center mr-8">
              <span class="w-2 h-2 rounded-full bg-purple-300"></span>
              <span class="ml-4 mr-1 group cursor-pointer font-semibold">Assembly</span>
              <span class="text-gray-500">2.1%</span>
            </li>
            <li class="flex items-center mr-8">
              <span class="w-2 h-2 rounded-full bg-red-300"></span>
              <span class="ml-4 mr-1 group cursor-pointer font-semibold">Javascript</span>
              <span class="text-gray-500">1.2%</span>
            </li>
          </ul>
        </div>
        <!-- end languages -->
      </div>
      <!-- end sidebar -->
    </div>
    <!-- end container -->

    <footer
      class="container mx-auto text-xs border-t border-gray-300 py-10 flex flex-col lg:flex-row items-center justify-between"
    >
      <ul class="flex items-center space-x-12 mb-2 lg:mb-0">
        <li>&copy; 2021 GitHub, Inc.</li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Terms</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Privacy</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Security</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Status</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Docs</a>
        </li>
      </ul>
      <svg
        class="hidden lg:block w-6 h-6 fill-current text-gray-400 hover:text-gray-800"
        aria-hidden="true"
        viewBox="0 0 16 16"
        version="1.1"
        data-view-component="true"
      >
        <path
          fill-rule="evenodd"
          d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
        />
      </svg>

      <ul class="flex items-center space-x-12">
        <li>
          <a href="#" class="text-blue-600 hover:underline">Contact GitHub</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Pricing</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">API</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Training</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">Blog</a>
        </li>
        <li>
          <a href="#" class="text-blue-600 hover:underline">About</a>
        </li>
      </ul>
    </footer>
    <!-- <primary-button>tailwindcss component test</primary-button> -->
  </div>
</template>

<script>
// import PrimaryButton from './components/PrimaryButton.vue'

export default {
  // components: { PrimaryButton }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
