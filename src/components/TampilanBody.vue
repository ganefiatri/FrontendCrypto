<template>
    <body>
        <div class="flex flex-wrap gap-7 py-5 sm:px-6 px-4">
             <div class="w-64 p-4">
                <div class="flex justify-center items-center flex-col">
                    <label for="checked-toggle" class="inline-flex relative items-center cursor-pointer">
                    <input type="checkbox" value="" id="checked-toggle" class="sr-only peer" checked>
                    <div class="w-11 h-6 bg-gray-200 rounded-full peer peer-focus:ring-4 peer-focus:ring-blue-300 dark:peer-focus:ring-blue-800 dark:bg-gray-700 peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:left-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-blue-600"></div>
                    <span class="ml-3 text-sm font-medium text-gray-900 dark:text-gray-300">Stacked Only</span>
                    </label>
                </div>
            </div>
        </div>
        <div class="flex flex-wrap items-center justify-center gap-7 py-20 sm:px-6 px-4">
            <div class="w-64 p-4 rounded border hover:shadow-lg">
                <div class="flex justify-center items-center flex-col">
                    <div>
                        <img src="../assets/dolarsign.png" alt="avatar" />
                    </div>
                    <div class="flex justify-center items-center flex-col mt-3">
                        <p class="text-2xl font-medium leading-none text-gray-800">SPY-BUSD</p>
                        <p>
                            <button type="button" class="text-white bg-gradient-to-r from-cyan-500 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-cyan-300 dark:focus:ring-cyan-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">Core</button>
                            <button type="button" class="text-white bg-gradient-to-br from-pink-500 to-orange-400 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-pink-200 dark:focus:ring-pink-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">40582X</button>
                        </p>
                    </div>
                </div>
                <div class="flex items-center justify-between mt-8">
                    <h1 class="text-2xs leading-normal text-gray-800">APY:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">1,110.49%</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Earn:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">SPY + Fees</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Harvest Lockup:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">324 Hour (s)</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Next Harvest In:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">--:--:--</p>
                    </div>
                </div>
                
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Connect Wallet</p>
                    </button>
                </div>
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Details Product</p>
                    </button>
                </div>
            </div>
            <div class="w-64 p-4 rounded border hover:shadow-lg">
                <div class="flex justify-center items-center flex-col">
                    <div>
                        <img src="../assets/dolarsign.png" alt="avatar" />
                    </div>
                    <div class="flex justify-center items-center flex-col mt-3">
                        <p class="text-2xl font-medium leading-none text-gray-800">SPY-BNB</p>
                        <p>
                            <button type="button" class="text-white bg-gradient-to-r from-cyan-500 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-cyan-300 dark:focus:ring-cyan-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">Core</button>
                            <button type="button" class="text-white bg-gradient-to-br from-pink-500 to-orange-400 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-pink-200 dark:focus:ring-pink-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">42178X</button>
                        </p>
                    </div>
                </div>
                <div class="flex items-center justify-between mt-8">
                    <h1 class="text-2xs leading-normal text-gray-800">APY:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">710.49%</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Earn:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">SPY + Fees</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Harvest Lockup:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">324 Hour (s)</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Next Harvest In:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">--:--:--</p>
                    </div>
                </div>
                
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Connect Wallet</p>
                    </button>
                </div>
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Details Product</p>
                    </button>
                </div>
            </div>
            <div class="w-64 p-4 rounded border hover:shadow-lg">
                <div class="flex justify-center items-center flex-col">
                    <div>
                        <img src="../assets/dolarsign.png" alt="avatar" />
                    </div>
                    <div class="flex justify-center items-center flex-col mt-3">
                        <p class="text-2xl font-medium leading-none text-gray-800">SPY-USDC</p>
                        <p>
                            <button type="button" class="text-white bg-gradient-to-r from-cyan-500 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-cyan-300 dark:focus:ring-cyan-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">Core</button>
                            <button type="button" class="text-white bg-gradient-to-br from-pink-500 to-orange-400 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-pink-200 dark:focus:ring-pink-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">20240X</button>
                        </p>
                    </div>
                </div>
                <div class="flex items-center justify-between mt-8">
                    <h1 class="text-2xs leading-normal text-gray-800">APY:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">1,410.49%</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Earn:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">SPY + Fees</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Harvest Lockup:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">324 Hour (s)</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Next Harvest In:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">--:--:--</p>
                    </div>
                </div>
                
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Connect Wallet</p>
                    </button>
                </div>
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Details Product</p>
                    </button>
                </div>
            </div>
            <div class="w-64 p-4 rounded border hover:shadow-lg">
                <div class="flex justify-center items-center flex-col">
                    <div>
                        <img src="../assets/dolarsign.png" alt="avatar" />
                    </div>
                    <div class="flex justify-center items-center flex-col mt-3">
                        <p class="text-2xl font-medium leading-none text-gray-800">SPY NFT Pool (V4)</p>
                        <p>
                            <button type="button" class="text-white bg-gradient-to-r from-cyan-500 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-cyan-300 dark:focus:ring-cyan-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">Core</button>
                            <button type="button" class="text-white bg-gradient-to-br from-pink-500 to-orange-400 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-pink-200 dark:focus:ring-pink-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">10582X</button>
                        </p>
                    </div>
                </div>
                <div class="flex items-center justify-between mt-8">
                    <h1 class="text-2xs leading-normal text-gray-800">APY:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">1,510.49%</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Earn:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">SPY + Fees</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Harvest Lockup:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">324 Hour (s)</p>
                    </div>
                </div>
                <div class="flex items-center justify-between">
                    <h1 class="text-2xs leading-normal text-gray-800">Next Harvest In:</h1>
                    <div class="p-1 flex justify-between">
                        <p class="text-sm font-semibold leading-normal text-gray-800">--:--:--</p>
                    </div>
                </div>
                
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Connect Wallet</p>
                    </button>
                </div>
                <div class="w-56 h-9 mt-2">
                    <button role="button" aria-label="message" class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-300 hover:bg-gray-100 flex items-center justify-center flex-1 h-full py-3 px-20 bg-gray-50 border rounded border-gray-200">
                        <p class="text-sm font-medium leading-none text-gray-600">Details Product</p>
                    </button>
                </div>
            </div>
        </div>
    </body>
</template>

<script>
//import Chart from "chart.js";
export default {
    name: "MyComponent",
    data() {
        return {};
    },
};
</script>

<style scoped></style>
