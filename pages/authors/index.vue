<template>
    <main class="py-8 px-32 flex flex-col gap-16">
        <div>
            <svg class="w-full" width="1520" height="231" viewBox="0 0 1520 231" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M166.721 225.89H216.953L134.363 4.62257H83.2064L0 225.89H47.1503L64.0998 178.432H150.08L166.721 225.89ZM107.552 55.7791L137.137 141.143H77.3511L107.552 55.7791Z" fill="black"/> <path d="M416.393 4.62257H369.551V142.684C369.551 170.111 356.3 188.601 325.482 188.601C294.357 188.601 281.106 170.111 281.106 142.684V4.62257H234.264V141.759C234.264 194.148 266.93 230.513 325.482 230.513C383.111 230.513 416.393 194.148 416.393 141.759V4.62257Z" fill="black"/> <path d="M560.117 225.89V46.8421H630.072V4.62257H443.628V46.8421H513.275V225.89H560.117Z" fill="black"/> <path d="M704.856 225.89V132.206H800.698V225.89H847.54V4.62257H800.698V91.8352H704.856V4.62257H658.014V225.89H704.856Z" fill="black"/> <path d="M993.211 230.513C1057.31 230.513 1106.93 181.205 1106.93 114.948C1106.93 48.6912 1057.31 0 993.211 0C929.42 0 880.112 48.6912 880.112 114.948C880.112 181.205 929.42 230.513 993.211 230.513ZM993.211 188.601C952.841 188.601 928.187 155.627 928.187 114.948C928.187 74.2694 952.841 41.9114 993.211 41.9114C1033.89 41.9114 1058.54 74.2694 1058.54 114.948C1058.54 155.627 1033.89 188.601 993.211 188.601Z" fill="black"/> <path d="M1186.07 225.89V147.614H1215.35L1265.27 225.89H1321.05L1264.04 140.526C1295.48 130.049 1313.97 106.319 1313.97 76.4266C1313.97 30.509 1281.61 4.62257 1225.83 4.62257H1139.23V225.89H1186.07ZM1186.07 43.4522H1223.67C1252.02 43.4522 1267.12 54.5464 1267.12 76.4266C1267.12 97.9987 1252.02 109.093 1223.67 109.093H1186.07V43.4522Z" fill="black"/> <path d="M1520 157.168C1520 124.501 1499.04 106.627 1460.21 98.9232L1422.31 91.2189C1406.28 88.1372 1392.42 81.6656 1392.42 66.5651C1392.42 51.1565 1405.36 38.2133 1428.16 38.2133C1451.59 38.2133 1467.61 53.9301 1469.15 77.043H1516.61C1513.53 30.8172 1477.16 1.84903 1427.55 1.84903C1379.78 1.84903 1344.96 30.2008 1344.96 69.6469C1344.96 106.319 1370.84 124.501 1404.44 130.973L1440.8 138.061C1459.6 141.759 1470.38 150.08 1470.38 163.947C1470.38 181.821 1453.43 192.299 1429.71 192.299C1401.05 192.299 1385.33 176.582 1384.1 152.237H1336.64C1340.03 199.079 1374.85 228.972 1430.63 228.972C1486.1 228.972 1520 199.387 1520 157.168Z" fill="black"/> </svg> 
        </div>
        <div v-for="(item, index) in items.slice().reverse()" class="flex flex-col gap-8">
            <div class="border-b py-8 first:pt-0 flex gap-8 items-center px-8">
                <!-- <div class="font-semibold">{{ '0' + (items.length - index).toString() }}</div>
                <NuxtImg src="/podcast-example.png" />
                <div class="font-semibold text-2xl w-full">The Problem of today’s cultural development</div>
                <div class="flex gap-8 items-center justify-end text-sm w-full">
                    <div class="flex gap-2">
                        <b>Date</b>
                        <div>16 March 2022</div>
                    </div>
                    <div class="flex gap-2">
                        <b>Duration</b>
                        <div>1 Min</div>
                    </div>
                    <ButtonText>Listen</ButtonText>
                </div> -->
                <NuxtImg src="/author-avatar-example.png" class="rounded-full" />
                <div class="font-bold text-lg w-full">Jakob Gronberg</div>
                <div class="flex gap-8 items-center justify-end text-sm w-full">
                    <div class="flex gap-2">
                        <b>Job</b>
                        <div>Artist</div>
                    </div>
                    <div class="flex gap-2">
                        <b>City</b>
                        <div>Berlin</div>
                    </div>
                    <ButtonText>About</ButtonText>
                </div>
            </div>
        </div>
    </main>
</template>

<script setup lang="ts">
    const items = ref([{  }, {  }, {  }, {  }, {  }])
</script>

<style scoped>

</style>