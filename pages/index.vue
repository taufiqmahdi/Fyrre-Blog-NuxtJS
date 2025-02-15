<template>
    <main class="p-8 flex flex-col gap-8">
        <div>
            <svg class="w-full" width="1520" height="216" viewBox="0 0 1520 216" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M160.207 212.622H208.476L129.113 0H79.9553L0 212.622H45.308L61.5952 167.018H144.216L160.207 212.622ZM103.35 49.1577L131.778 131.186H74.3288L103.35 49.1577Z" fill="black"/> <path d="M279.39 212.622V137.405H307.523L355.496 212.622H409.095L354.311 130.594C384.517 120.525 402.284 97.7232 402.284 68.9985C402.284 24.875 371.191 0 317.591 0H234.378V212.622H279.39ZM279.39 37.3125H315.518C342.762 37.3125 357.273 47.9732 357.273 68.9985C357.273 89.7276 342.762 100.388 315.518 100.388H279.39V37.3125Z" fill="black"/> <path d="M528.688 212.622V40.5699H595.91V0H416.751V40.5699H483.676V212.622H528.688Z" fill="black"/> <path d="M759.865 96.5387C746.539 82.0283 740.616 74.0327 740.616 63.0759C740.616 50.9345 749.204 42.3467 760.753 42.3467C772.894 42.3467 781.482 49.75 782.963 63.6681H821.164C820.868 31.0937 796.881 9.47619 760.753 9.47619C724.921 9.47619 698.269 31.9821 698.269 62.7797C698.269 74.9211 701.823 85.5818 709.226 95.9464C686.72 108.68 673.098 127.632 673.098 150.138C673.098 189.82 701.527 215.287 745.947 215.287C765.491 215.287 783.555 207.884 799.546 193.966L817.018 212.622H867.656L823.237 164.649C832.121 148.065 838.043 127.632 838.339 109.865H800.731C800.435 119.341 799.546 128.817 797.769 137.405L759.865 96.5387ZM712.484 147.769C712.484 135.628 719.295 125.856 730.252 120.229L778.521 171.46C770.229 178.271 759.865 181.824 748.908 181.824C724.921 181.824 712.484 166.722 712.484 147.769Z" fill="black"/> <path d="M1089.26 212.622V172.052H996.871V0H951.859V212.622H1089.26Z" fill="black"/> <path d="M1165.18 212.622V0H1120.17V212.622H1165.18Z" fill="black"/> <path d="M1253.67 212.622V131.482H1331.55V92.6889H1253.67V39.0893H1346.06V0H1208.66V212.622H1253.67Z" fill="black"/> <path d="M1520 173.533H1421.98V122.598H1509.04V83.805H1421.98V39.0893H1517.93V0H1376.97V212.622H1520V173.533Z" fill="black"/> </svg>
        </div>
        <div class="bg-black text-white flex gap-4 p-4">
            <div class="font-bold text-lg text-nowrap">NEWS TICKER+++</div>
            <div class="text-nowrap font-light overflow-hidden">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit +++ Lorem ipsum dolor sit amet, consectetur adipiscing elit +++ Lorem ipsum dolor sit amet, consectetur adipiscing elit +++ Lorem ipsum dolor sit amet, consectetur adipiscing elit +++ 
            </div>
        </div> 
        <div class="flex gap-8">
            <div class="text-8xl font-bold flex-1">DON'T CLOSE<br /> YOUR EYES</div>
            <div class="flex flex-col gap-4 place-content-between flex-1">
                <div class="">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Egestas dui id ornare arcu odio ut sem. Cras ornare arcu dui vivamus arcu felis bibendum ut. Porttitor leo a diam.</div>
                <div class="flex gap-4 justify-between">
                    <div class="flex gap-4 items-center text-sm">
                        <div class="flex gap-2">
                            <b>Text</b>
                            <div>Jakob Gronber</div>
                        </div>
                        <div class="flex gap-2">
                            <b>Date</b>
                            <div>16 March 2022</div>
                        </div>
                        <div class="flex gap-2">
                            <b>Duration</b>
                            <div>1 Min</div>
                        </div>
                    </div>
                    <Label>
                        Label
                    </Label>
                </div>
            </div>
        </div>       
        <div>
            <NuxtImg
            format="webp"
            src="/hero-banner.png"
            alt=""
            class="w-full"
          />
        </div>
        <div class="flex gap-8">
            <div class="w-3/4 flex flex-col gap-8">
                <ArticleFeed />
                <hr>
                <ArticleFeed />
                <ButtonText to="/articles" labelPosition="end">All Articles</ButtonText>
            </div>
            <div class="w-1/4 flex flex-col gap-8">
                <div class="flex flex-col gap-4">
                    <div class="font-bold">
                        PRINTMAGAZINE
                    </div>
                    <div class="font-bold text-4xl">
                        03/2022
                    </div>
                </div>
                <div class="flex flex-col gap-4">
                    <Magazine />
                    <Button>
                        Button
                    </Button>
                </div>
                <div class="flex flex-col gap-4">
                    <div class="font-semibold">MOST POPULAR</div>
                    <PopularArticle index="01" />
                    <hr />
                    <PopularArticle index="02" />
                </div>
                <div class="bg-[#F8F8F8] p-4 flex flex-col gap-4">
                    <div class="font-semibold">NEWSLETTER</div>
                    <div class="text-3xl font-bold">Design News to<br /> your inbox</div>
                    <form class="flex flex-col gap-2 items-end">
                        <input class="bg-white px-4 py-2 w-full" type="email" name="email" id="email" placeholder="Email">
                        <Button>Sign Up</Button>
                    </form>
                </div>
            </div>
        </div>
        <hr />
        <div class="flex flex-col gap-8">
            <div class="flex gap-4 justify-between">
                <div class="text-8xl font-bold flex-1">PODCAST</div>
                <ButtonText to="/episodes" labelPosition="end">All Episodes</ButtonText>
            </div>
            <div class="flex">
                <PodcastItem />
                <PodcastItem />
                <PodcastItem />
            </div>
        </div>
        <hr />
        <div class="flex flex-col gap-8">
            <div class="flex gap-4 justify-between">
                <div class="text-8xl font-bold flex-1">AUTHORS</div>
                <ButtonText to="/episodes" labelPosition="end">All Authors</ButtonText>
            </div>
            <div class="grid grid-cols-2">
                <AuthorsItem />
                <AuthorsItem />
                <AuthorsItem />
                <AuthorsItem />
                <AuthorsItem />
                <AuthorsItem />
            </div>
        </div>
    </main>
</template>

<script setup lang="ts">
    useSeoMeta({
    title: "Fyrre - Webflow HTML Website Template",
    //   description: "Recipes for you to cook!",
    //   ogTitle: "Nuxtcipes",
    //   ogDescription: "Recipes for you to cook!",
    //   ogImage: "/nuxt-course-hero.png",
    //   ogUrl: `http:localhost:3000`,
    //   twitterTitle: "Nuxtcipes",
    //   twitterDescription: "Recipes for you to cook!",
    //   twitterImage: "/nuxt-course-hero.png",
    //   twitterCard: "summary",
    });
</script>

<style scoped>

</style>