<template>
    <div class="flex justify-center">
        <div class="w-full mt-[50px]">
            <div class="text-[#464A50] font-bold text-[18px] ml-[20px]">Recent results</div>
            <div>
                <div class="relative overflow-x-auto shadow-md sm:rounded-lg ml-[20px] mt-[px]">
                    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
                        <caption
                            class="text-lg font-semibold text-left text-[#464A50] bg-white dark:text-white dark:bg-gray-800 pt-5 pl-5">
                            Top 3 Scorers
                            <p class="mt-1 text-sm font-normal text-[#464A50] dark:text-gray-400">
                                See the top scorers within each workbook
                            </p>
                            <div
                                class="mt-[20px] bg-[#EBECF0] text-lg font-semibold text-left text-[#464A50] -mx-[20px] pl-[20px] py-[10px]">
                                UX Research
                            </div>
                        </caption>
                        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                            <tr>
                                <th scope="col" class="px-6 py-3">Name</th>
                                <th scope="col" class="px-6 py-3">Email Address</th>
                                <th scope="col" class="px-6 py-3">Role</th>
                                <th scope="col" class="px-6 py-3">Score</th>
                                <th scope="col" class="px-6 py-3">Time used</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Olivia Rhye
                                </th>
                                <td class="px-6 py-4">olivia@untitledui.com</td>
                                <td class="px-6 py-4">Product Designer</td>
                                <td class="px-6 py-4">95%</td>
                                <td class="px-6 py-4">7:29</td>
                            </tr>
                            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Phoenix Baker
                                </th>
                                <td class="px-6 py-4">phoenix@untitledui.com</td>
                                <td class="px-6 py-4">Product Manager</td>
                                <td class="px-6 py-4">82%</td>
                                <td class="px-6 py-4">19:30</td>
                            </tr>
                            <tr class="bg-white dark:bg-gray-800">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Lana Steiner
                                </th>
                                <td class="px-6 py-4">lana@untitledui.com</td>
                                <td class="px-6 py-4">Frontend Developer</td>
                                <td class="px-6 py-4">75%</td>
                                <td class="px-6 py-4">21:45</td>
                            </tr>
                        </tbody>
                    </table>
                    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
                        <caption>
                            <div class=" bg-[#EBECF0] text-lg font-semibold text-left text-[#464A50] pl-[20px] py-[10px]">
                                UX Principle
                            </div>
                        </caption>
                        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                            <tr>
                                <th scope="col" class="px-6 py-3">Name</th>
                                <th scope="col" class="px-6 py-3">Email Address</th>
                                <th scope="col" class="px-6 py-3">Role</th>
                                <th scope="col" class="px-6 py-3">Score</th>
                                <th scope="col" class="px-6 py-3">Time used</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Olivia Rhye
                                </th>
                                <td class="px-6 py-4">olivia@untitledui.com</td>
                                <td class="px-6 py-4">Product Designer</td>
                                <td class="px-6 py-4">95%</td>
                                <td class="px-6 py-4">7:29</td>
                            </tr>
                            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Demi Wilkinson
                                </th>
                                <td class="px-6 py-4"> demi@untitledui.com</td>
                                <td class="px-6 py-4">Backend Developer</td>
                                <td class="px-6 py-4">95%</td>
                                <td class="px-6 py-4">19:30</td>
                            </tr>
                            <tr class="bg-white dark:bg-gray-800">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Candice Wu
                                </th>
                                <td class="px-6 py-4">candice@untitledui.com</td>
                                <td class="px-6 py-4">Fullstack Developer</td>
                                <td class="px-6 py-4">75%</td>
                                <td class="px-6 py-4">21:45</td>
                            </tr>
                        </tbody>
                    </table>
                    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
                        <caption>
                            <div class=" bg-[#EBECF0] text-lg font-semibold text-left text-[#464A50] pl-[20px] py-[10px]">
                                Typography
                            </div>
                        </caption>
                        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                            <tr>
                                <th scope="col" class="px-6 py-3">Name</th>
                                <th scope="col" class="px-6 py-3">Email Address</th>
                                <th scope="col" class="px-6 py-3">Role</th>
                                <th scope="col" class="px-6 py-3">Score</th>
                                <th scope="col" class="px-6 py-3">Time used</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Phoenix Baker
                                </th>
                                <td class="px-6 py-4">phoenix@untitledui.com</td>
                                <td class="px-6 py-4">Product Manager</td>
                                <td class="px-6 py-4">82%</td>
                                <td class="px-6 py-4">19:30</td>
                            </tr>
                            <tr class="bg-white dark:bg-gray-800">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Lana Steiner
                                </th>
                                <td class="px-6 py-4">lana@untitledui.com</td>
                                <td class="px-6 py-4">Frontend Developer</td>
                                <td class="px-6 py-4">75%</td>
                                <td class="px-6 py-4">21:45</td>
                            </tr>
                            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                                <th scope="row"
                                    class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                    Demi Wilkinson
                                </th>
                                <td class="px-6 py-4"> demi@untitledui.com</td>
                                <td class="px-6 py-4">Backend Developer</td>
                                <td class="px-6 py-4">95%</td>
                                <td class="px-6 py-4">19:30</td>
                            </tr>
                            

                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>
