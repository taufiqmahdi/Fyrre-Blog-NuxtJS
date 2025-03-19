<template>
    <main class="py-8 px-32 flex flex-col gap-16">
        <div class="flex items-center justify-between gap-4">
            <ButtonText labelPosition="start">
                Go Back
            </ButtonText>
            <h2 class="uppercase font-bold text-lg">Author</h2>
        </div>
        <div class="flex flex-col gap-8">
            <div class="max-w-4xl grid grid-cols-3 gap-8 self-center">
                <div class="flex flex-col gap-4">
                    <NuxtImg src="/author-avatar-example.png" class="rounded-full" />
                    <hr>
                    <div class="flex flex-col gap-4 text-sm">
                        <div class="flex gap-4 justify-between items-center">
                            <div class="font-bold uppercase">Follow</div>
                            <div class="font-light flex items-center gap-4">
                                <svg width="20" height="21" viewBox="0 0 20 21" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M10.0003 8.00008C9.33729 8.00008 8.7014 8.26347 8.23256 8.73232C7.76372 9.20116 7.50033 9.83704 7.50033 10.5001C7.50033 11.1631 7.76372 11.799 8.23256 12.2679C8.7014 12.7367 9.33729 13.0001 10.0003 13.0001C10.6634 13.0001 11.2993 12.7367 11.7681 12.2679C12.2369 11.799 12.5003 11.1631 12.5003 10.5001C12.5003 9.83704 12.2369 9.20116 11.7681 8.73232C11.2993 8.26347 10.6634 8.00008 10.0003 8.00008ZM10.0003 6.33342C11.1054 6.33342 12.1652 6.7724 12.9466 7.5538C13.728 8.33521 14.167 9.39501 14.167 10.5001C14.167 11.6052 13.728 12.665 12.9466 13.4464C12.1652 14.2278 11.1054 14.6668 10.0003 14.6668C8.89526 14.6668 7.83545 14.2278 7.05405 13.4464C6.27265 12.665 5.83366 11.6052 5.83366 10.5001C5.83366 9.39501 6.27265 8.33521 7.05405 7.5538C7.83545 6.7724 8.89526 6.33342 10.0003 6.33342V6.33342ZM15.417 6.12508C15.417 6.40135 15.3072 6.6663 15.1119 6.86165C14.9165 7.057 14.6516 7.16675 14.3753 7.16675C14.0991 7.16675 13.8341 7.057 13.6388 6.86165C13.4434 6.6663 13.3337 6.40135 13.3337 6.12508C13.3337 5.84881 13.4434 5.58386 13.6388 5.38851C13.8341 5.19316 14.0991 5.08342 14.3753 5.08342C14.6516 5.08342 14.9165 5.19316 15.1119 5.38851C15.3072 5.58386 15.417 5.84881 15.417 6.12508V6.12508ZM10.0003 3.83342C7.93866 3.83342 7.60199 3.83925 6.64283 3.88175C5.98949 3.91258 5.55116 4.00008 5.14449 4.15841C4.80417 4.28336 4.4965 4.48363 4.24449 4.74425C3.98366 4.99625 3.78312 5.3039 3.65783 5.64425C3.49949 6.05258 3.41199 6.49008 3.38199 7.14258C3.33866 8.06258 3.33366 8.38425 3.33366 10.5001C3.33366 12.5618 3.33949 12.8984 3.38199 13.8576C3.41283 14.5101 3.50033 14.9493 3.65783 15.3551C3.79949 15.7176 3.96616 15.9784 4.24283 16.2551C4.52366 16.5351 4.78449 16.7026 5.14283 16.8409C5.55449 17.0001 5.99283 17.0884 6.64283 17.1184C7.56283 17.1618 7.88449 17.1668 10.0003 17.1668C12.062 17.1668 12.3987 17.1609 13.3578 17.1184C14.0095 17.0876 14.4487 17.0001 14.8553 16.8426C15.1951 16.717 15.5026 16.5171 15.7553 16.2576C16.0362 15.9768 16.2037 15.7159 16.342 15.3576C16.5003 14.9468 16.5887 14.5076 16.6187 13.8576C16.662 12.9376 16.667 12.6159 16.667 10.5001C16.667 8.43842 16.6612 8.10175 16.6187 7.14258C16.5878 6.49092 16.5003 6.05092 16.342 5.64425C16.2164 5.30425 16.0162 4.99672 15.7562 4.74425C15.5043 4.48329 15.1966 4.28272 14.8562 4.15758C14.4478 3.99925 14.0095 3.91175 13.3578 3.88175C12.4378 3.83842 12.1162 3.83342 10.0003 3.83342ZM10.0003 2.16675C12.2645 2.16675 12.547 2.17508 13.4353 2.21675C14.3228 2.25841 14.927 2.39758 15.4587 2.60425C16.0087 2.81591 16.472 3.10258 16.9353 3.56508C17.3591 3.98166 17.687 4.48557 17.8962 5.04175C18.102 5.57258 18.242 6.17758 18.2837 7.06508C18.3228 7.95342 18.3337 8.23592 18.3337 10.5001C18.3337 12.7643 18.3253 13.0467 18.2837 13.9351C18.242 14.8226 18.102 15.4267 17.8962 15.9584C17.6876 16.5149 17.3596 17.0189 16.9353 17.4351C16.5186 17.8587 16.0148 18.1865 15.4587 18.3959C14.9278 18.6018 14.3228 18.7418 13.4353 18.7834C12.547 18.8226 12.2645 18.8334 10.0003 18.8334C7.73616 18.8334 7.45366 18.8251 6.56533 18.7834C5.67783 18.7418 5.07366 18.6018 4.54199 18.3959C3.9856 18.1871 3.4816 17.8592 3.06533 17.4351C2.6415 17.0186 2.3136 16.5146 2.10449 15.9584C1.89783 15.4276 1.75866 14.8226 1.71699 13.9351C1.67783 13.0467 1.66699 12.7643 1.66699 10.5001C1.66699 8.23592 1.67533 7.95342 1.71699 7.06508C1.75866 6.17675 1.89783 5.57342 2.10449 5.04175C2.31302 4.48523 2.641 3.98118 3.06533 3.56508C3.48172 3.14111 3.98568 2.81319 4.54199 2.60425C5.07366 2.39758 5.67699 2.25841 6.56533 2.21675C7.45366 2.17758 7.73616 2.16675 10.0003 2.16675Z" fill="black"/> </svg>
                                <svg width="20" height="21" viewBox="0 0 20 21" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M18.4683 5.21327C17.8321 5.49468 17.1574 5.6795 16.4666 5.76161C17.1947 5.32613 17.7397 4.64078 17.9999 3.83327C17.3166 4.23994 16.5674 4.52494 15.7866 4.67911C15.2621 4.11792 14.5669 3.74574 13.809 3.62043C13.0512 3.49511 12.2732 3.62368 11.596 3.98615C10.9187 4.34862 10.3802 4.92468 10.0642 5.62477C9.74812 6.32486 9.67221 7.10976 9.84825 7.85744C8.46251 7.78798 7.10686 7.42787 5.86933 6.80049C4.63179 6.17311 3.54003 5.29248 2.66492 4.21577C2.35516 4.74781 2.19238 5.35263 2.19326 5.96827C2.19326 7.1766 2.80826 8.24411 3.74326 8.86911C3.18993 8.85169 2.64878 8.70226 2.16492 8.43327V8.4766C2.16509 9.28136 2.44356 10.0613 2.95313 10.6842C3.46269 11.307 4.17199 11.7345 4.96075 11.8941C4.4471 12.0333 3.90851 12.0538 3.38576 11.9541C3.60814 12.6468 4.04159 13.2526 4.62541 13.6867C5.20924 14.1208 5.9142 14.3614 6.64159 14.3749C5.91866 14.9427 5.0909 15.3624 4.20566 15.6101C3.32041 15.8577 2.39503 15.9285 1.48242 15.8183C3.0755 16.8428 4.93 17.3867 6.82409 17.3849C13.2349 17.3849 16.7408 12.0741 16.7408 7.46827C16.7408 7.31827 16.7366 7.16661 16.7299 7.01827C17.4123 6.52508 18.0013 5.91412 18.4691 5.21411L18.4683 5.21327Z" fill="black"/> </svg>
                                <svg width="20" height="21" viewBox="0 0 20 21" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M17.9528 5.91492C18.3337 7.39992 18.3337 10.4999 18.3337 10.4999C18.3337 10.4999 18.3337 13.5999 17.9528 15.0849C17.7412 15.9058 17.122 16.5516 16.3378 16.7699C14.9137 17.1666 10.0003 17.1666 10.0003 17.1666C10.0003 17.1666 5.08949 17.1666 3.66283 16.7699C2.87533 16.5483 2.25699 15.9033 2.04783 15.0849C1.66699 13.5999 1.66699 10.4999 1.66699 10.4999C1.66699 10.4999 1.66699 7.39992 2.04783 5.91492C2.25949 5.09409 2.87866 4.44825 3.66283 4.22992C5.08949 3.83325 10.0003 3.83325 10.0003 3.83325C10.0003 3.83325 14.9137 3.83325 16.3378 4.22992C17.1253 4.45159 17.7437 5.09659 17.9528 5.91492ZM8.33366 13.4166L13.3337 10.4999L8.33366 7.58325V13.4166Z" fill="black"/> </svg>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-span-2 flex flex-col gap-8">
                    <div class="font-bold text-8xl uppercase">Louise Jensen</div>
                    <div class="font-medium">
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Egestas dui id ornare arcu odio ut sem. Cras ornare arcu dui vivamus arcu felis bibendum ut. Porttitor leo a diam.
                    </div>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Egestas dui id ornare arcu odio ut sem. Cras ornare arcu dui vivamus arcu felis bibendum ut. Porttitor leo a diam.
    
                        Porttitor rhoncus dolor purus non enim praesent elementum. Eget dolor morbi non arcu risus quis varius. Posuere ac ut consequat semper viverra nam libero. In ornare quam viverra orci sagittis eu. Tristique risus nec feugiat in fermentum posuere urna nec. Tempus quam pellentesque nec nam aliquam sem et. Convallis a cras semper auctor neque vitae tempus quam pellentesque. Sollicitudin ac orci phasellus egestas tellus rutrum tellus pellentesque. Sed egestas egestas fringilla phasellus faucibus scelerisque eleifend donec pretium. Sit amet porttitor eget dolor morbi non arcu risus. Justo eget magna fermentum iaculis eu non diam phasellus. Sit amet luctus venenatis lectus magna fringilla. Neque vitae tempus quam pellentesque nec nam.
    
    Tellus orci ac auctor augue mauris augue neque gravida. Tempus imperdiet nulla malesuada pellentesque elit eget gravida cum sociis. Id eu nisl nunc mi ipsum faucibus vitae aliquet. Duis convallis convallis tellus id interdum velit laoreet id. Vulputate mi sit amet mauris commodo quis. Semper viverra nam libero justo laoreet sit amet. Eget nullam non nisi est sit. Nibh cras pulvinar mattis nunc sed blandit libero. Ac felis donec et odio pellentesque diam volutpat. Quis varius quam quisque id diam vel quam elementum. Felis bibendum ut tristique et egestas quis ipsum suspendisse ultrices. Id diam vel quam elementum pulvinar etiam non. Non consectetur a erat nam at lectus urna duis convallis.
                    </p>
                </div>
            </div>
        </div>
        <hr>
        <div class="flex flex-col gap-8">
            <div class="flex gap-8 items-center justify-between">
                <h1 class="text-4xl font-bold">
                    Articles by Louise Jensen
                </h1>
            </div>
            <div class="grid grid-cols-2">
                <ArticleItem v-for="(item, index) in items.slice().reverse()" :key="index" />
            </div>
        </div>
    </main>
</template>

<script setup lang="ts">
    const items = ref([{  }, {  }, {  }, {  }, {  }])
</script>

<style scoped>

</style>