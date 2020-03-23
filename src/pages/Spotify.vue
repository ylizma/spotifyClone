<template>
    <div>
        <div class="flex flex-col h-screen text-sm text-gray-400">
            <div class=" flex-1 flex overflow-y-hidden">
                <div class="sidebar font-semibold bg-gray-900-spotify w-48 flex-none overflow-y-auto flex flex-col justify-between">
                    <ul class="py-6">
                        <li class="border-l-4 border-green-600 ">
                            <a href="#" class="flex items-center text-white mx-4 mr-3 mt-4 group">
                                <svg class="" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                                width="24" height="24"
                                viewBox="0 0 172 172"
                                style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M86,15.05l-78.82617,70.95h21.49283v64.5h114.66667v-64.5h21.49283zM100.33333,136.16667h-28.66667v-21.5c0,-7.90483 6.4285,-14.33333 14.33333,-14.33333c7.90483,0 14.33333,6.4285 14.33333,14.33333zM129,136.16667h-14.33333v-21.5c0,-15.83117 -12.8355,-28.66667 -28.66667,-28.66667c-15.83117,0 -28.66667,12.8355 -28.66667,28.66667v21.5h-14.33333v-63.13117l43,-38.7l43,38.7z"></path></g></g></svg>
                                <span class="ml-3">Home</span>
                            </a>
                        </li>
                        <li class="border-l-4 border-transparent ">
                            <a href="#" class="flex items-center hover:text-white  mx-4 mt-4 group">
                                <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                                width="20" height="20"
                                viewBox="0 0 172 172"
                                style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M58.48,13.76v6.88h92.88v116.96h-27.52v6.88h34.4v-130.72zM13.76,27.52v130.72h103.2v-3.44v-127.28zM20.64,34.4h89.44v116.96h-89.44zM61.92,68.8v20.64h-20.64v6.88h20.64v20.64h6.88v-20.64h20.64v-6.88h-20.64v-20.64z"></path></g></g></svg>
                                <span class="ml-3">Browse</span>
                            </a>
                        </li>
                        <li class="border-l-4 border-transparent ">
                            <a href="#" class="flex items-center hover:text-white mx-4 mt-4 group">
                                <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                                width="20" height="20"
                                viewBox="0 0 172 172"
                                style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M35.62953,17.17313c-0.77361,0.00206 -1.52394,0.2648 -2.12984,0.74578c-20.3585,15.72294 -33.49969,40.38247 -33.49969,68.08109c0,27.69863 13.14119,52.35816 33.49969,68.0811c0.96892,0.79275 2.29199,0.99661 3.4546,0.53228c1.16261,-0.46433 1.98122,-1.52356 2.13742,-2.76568c0.15621,-1.24212 -0.37465,-2.47105 -1.38608,-3.20879c-18.74054,-14.47338 -30.82563,-37.11385 -30.82563,-62.6389c0,-25.52505 12.08508,-48.16552 30.82563,-62.63891c1.18237,-0.89093 1.66218,-2.43837 1.19128,-3.84193c-0.4709,-1.40357 -1.78692,-2.34849 -3.26737,-2.34603zM136.26297,17.17313c-1.46087,0.04243 -2.7355,1.00321 -3.17857,2.39592c-0.44307,1.39271 0.04214,2.91335 1.20997,3.79205c18.74054,14.47338 30.82563,37.11385 30.82563,62.63891c0,25.52505 -12.08508,48.16552 -30.82563,62.6389c-1.01143,0.73774 -1.54228,1.96667 -1.38607,3.20879c0.15621,1.24212 0.97482,2.30134 2.13742,2.76567c1.1626,0.46433 2.48567,0.26048 3.45459,-0.53227c20.3585,-15.72294 33.49969,-40.38247 33.49969,-68.0811c0,-27.69863 -13.14119,-52.35816 -33.49969,-68.08109c-0.63462,-0.50443 -1.42699,-0.76855 -2.23735,-0.74578zM52.3189,34.89719c-0.77325,-0.02711 -1.53306,0.20723 -2.15672,0.66516c-15.76081,11.21715 -26.08219,29.6319 -26.08219,50.43765c0,20.80576 10.32138,39.2205 26.08219,50.43765c0.99855,0.77007 2.33837,0.93215 3.49174,0.42239c1.15337,-0.50976 1.93543,-1.60966 2.03814,-2.86646c0.10272,-1.2568 -0.49037,-2.46909 -1.54566,-3.15936c-14.02271,-9.98012 -23.1864,-26.30013 -23.1864,-44.83422c0,-18.53408 9.1637,-34.85409 23.1864,-44.83422c1.21933,-0.8423 1.76225,-2.37077 1.34747,-3.79352c-0.41478,-1.42274 -1.69402,-2.41999 -3.17497,-2.47508zM119.91625,34.89719c-1.52422,-0.04708 -2.89755,0.91485 -3.37418,2.36339c-0.47664,1.44854 0.05717,3.038 1.31153,3.9052c14.02271,9.98012 23.1864,26.30013 23.1864,44.83422c0,18.53408 -9.1637,34.85409 -23.1864,44.83422c-1.05529,0.69027 -1.64838,1.90256 -1.54566,3.15936c0.10272,1.2568 0.88478,2.3567 2.03814,2.86646c1.15337,0.50976 2.49319,0.34768 3.49174,-0.42239c15.76081,-11.21715 26.08219,-29.6319 26.08219,-50.43765c0,-20.80576 -10.32138,-39.2205 -26.08219,-50.43765c-0.55887,-0.41027 -1.22865,-0.64212 -1.92156,-0.66516zM68.9814,52.75563c-0.65827,-0.02151 -1.30887,0.14639 -1.87453,0.48375c-11.31323,6.53981 -18.94687,18.77252 -18.94687,32.76063c0,13.9881 7.63365,26.22081 18.94687,32.76063c1.64568,0.95179 3.75134,0.38927 4.70313,-1.2564c0.95179,-1.64568 0.38927,-3.75134 -1.2564,-4.70313c-9.26485,-5.35571 -15.5136,-15.31256 -15.5136,-26.8011c0,-11.48854 6.24874,-21.44538 15.5136,-26.8011c1.35125,-0.75377 2.03308,-2.31686 1.6663,-3.82003c-0.36678,-1.50317 -1.69192,-2.57656 -3.23849,-2.62324zM102.91781,52.75563c-1.52897,0.0878 -2.81582,1.1757 -3.15677,2.66876c-0.34096,1.49305 0.34607,3.03172 1.68537,3.77452c9.26485,5.35571 15.5136,15.31256 15.5136,26.8011c0,11.48854 -6.24874,21.44538 -15.5136,26.8011c-1.64568,0.95179 -2.20819,3.05745 -1.2564,4.70313c0.95179,1.64568 3.05745,2.20819 4.70313,1.2564c11.31323,-6.53981 18.94687,-18.77252 18.94687,-32.76063c0,-13.9881 -7.63365,-26.22081 -18.94687,-32.76063c-0.49509,-0.29551 -1.0565,-0.46186 -1.63266,-0.48375c-0.11415,-0.00569 -0.22851,-0.00569 -0.34265,0zM86,72.24c-7.55869,0 -13.76,6.20131 -13.76,13.76c0,7.55869 6.20131,13.76 13.76,13.76c7.55869,0 13.76,-6.20131 13.76,-13.76c0,-7.55869 -6.20131,-13.76 -13.76,-13.76zM86,79.12c3.84046,0 6.88,3.03954 6.88,6.88c0,3.84046 -3.03954,6.88 -6.88,6.88c-3.84046,0 -6.88,-3.03954 -6.88,-6.88c0,-3.84046 3.03954,-6.88 6.88,-6.88z"></path></g></g></svg>
                                <span class="ml-3">Radio</span>
                            </a>
                        </li>
                    </ul>
                    <div class="overflow-y-auto sidebar-spotify px-5 mt-2">
                    <h3 class="uppercase tracking-widest text-gray-500 font-normal text-xs">
                        Your Library
                    </h3>
                    <ul class="leading-extra-loose">
                        <li class="truncate"><a href="" class="hover:text-while">Made for You</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">Recently Played</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">Liked Songs</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">Albums</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">Albums</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">artists</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">Podcasts</a></li>
                    </ul>
                    <h3 class="mt-6 uppercase tracking-widest text-gray-500 font-normal text-xs">
                        Playlist
                    </h3>
                    <ul class="leading-extra-loose">
                        <li class="truncate"><a href="" class="hover:text-while">acoustic</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">i love you</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">dipps</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">rock and roll</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">Metal</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">artists</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">R&B right now</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">artists</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">R&B right now</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">artists</a></li>
                        <li class="truncate"><a href="" class="hover:text-while">R&B right now</a></li>
                    </ul>
                    </div>
                    <div class="three border-t border-gray-800 h-16 px-4 py-2 flex items-center group"> 
                        +<a href="" class="font-normal text-gray-500 ml-2 group-hover:text-white">New Playlist</a>
                    </div>
                </div>
                
                <div class="content content-spotify bg-gray-800-spotify flex-1 overflow-y-auto">
                    
                </div>

            </div>
            <div class="bg-gray-700-spotify flex-none h-22 px-5 flex items-center justify-between">
               <div class="left flex items-center ">
                 <a href=""> <img src="../assets/album01.jpg" alt="album cover" class="w-14 h-14"> </a>
                 <div class="ml-3">
                    <div>  <a class="hover:underline">Name of Song</a> </div>
                    <div>  <a href="" class="text-xs text-gray-500 hover:underline hover:text-white" >Artist Name</a> </div>
                 </div>
               </div>
               <div class="player-control flex flex-col justify-center">
                    <div class="flex justify-center">
                                        <button class="ml-8"><svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                                    width="20" height="20"
                                    viewBox="0 0 172 172"
                                    style=" fill:#000000;">
                                <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M129,10.75v21.5h-29.81445l-24.60743,38.38086l-24.60742,-38.38086h-39.22071v10.75h33.3418l24.10351,37.625l-24.10351,37.625h-33.3418v10.75h39.22071l24.60742,-38.38085l24.60743,38.38085h29.81445v21.5l26.875,-26.875l-26.875,-26.875v21.5h-23.93554l-24.10352,-37.625l24.10352,-37.625h23.93554v21.5l26.875,-26.875z"></path></g></g></svg></button>
                        <button class="ml-8">
                            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                            width="20" height="20"
                            viewBox="0 0 172 172"
                            style=" fill:#000000;">
                                <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M80.26667,34.4c-1.22139,0.00233 -2.41013,0.39465 -3.39297,1.11979c-0.05673,0.04004 -0.11273,0.0811 -0.16797,0.12318l-62.59635,45.51953c-0.00373,0.00374 -0.00746,0.00747 -0.0112,0.0112l-0.08958,0.06719c-1.58744,1.06365 -2.54064,2.84827 -2.54193,4.75911c0.00128,1.92516 0.96869,3.72117 2.57552,4.78151l62.82031,45.6987c0.98592,0.72741 2.17894,1.11985 3.40417,1.11979c3.16643,0 5.73333,-2.5669 5.73333,-5.73333c0.00001,-0.00746 0.00001,-0.01493 0,-0.02239v-38.76719l59.6625,43.40313c0.98592,0.72741 2.17894,1.11985 3.40417,1.11979c3.16643,0 5.73333,-2.5669 5.73333,-5.73333c0.00001,-0.00746 0.00001,-0.01493 0,-0.02239v-45.84427v-45.84427c0.00001,-0.00747 0.00001,-0.01493 0,-0.0224c0,-3.16643 -2.5669,-5.73333 -5.73333,-5.73333c-1.22522,-0.00006 -2.41824,0.39238 -3.40417,1.11979c-0.05297,0.04015 -0.10523,0.08121 -0.15677,0.12318l-59.50573,43.26875v-38.75599c0.00001,-0.00747 0.00001,-0.01493 0,-0.0224c0,-3.16643 -2.5669,-5.73333 -5.73333,-5.73333z"></path></g></g></svg>
                        </button>
                        <button class="ml-8">
                            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                            width="20" height="20"
                            viewBox="0 0 172 172"
                            style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M21.5,21.5v129h50.16667v-129zM100.33333,21.5v129h50.16667v-129z"></path></g></g></svg>
                        </button>
                        <button class="ml-8">
                                <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                                width="20" height="20"
                                viewBox="0 0 172 172"
                                style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M22.93333,34.4c-3.16643,0 -5.73333,2.5669 -5.73333,5.73333c-0.00001,0.00747 -0.00001,0.01493 0,0.0224v45.84427v45.84427c-0.00001,0.00746 -0.00001,0.01493 0,0.02239c0,3.16643 2.5669,5.73333 5.73333,5.73333c1.22139,-0.00232 2.41013,-0.39465 3.39297,-1.11979h0.0112c0.05297,-0.04015 0.10523,-0.08121 0.15677,-0.12318l59.50573,-43.26875v38.75599c-0.00001,0.00746 -0.00001,0.01493 0,0.02239c0,3.16643 2.5669,5.73333 5.73333,5.73333c1.22139,-0.00232 2.41013,-0.39465 3.39297,-1.11979h0.0112c0.05297,-0.04015 0.10523,-0.08121 0.15677,-0.12318l62.60755,-45.53073c1.6415,-1.05596 2.63304,-2.87449 2.63151,-4.8263c-0.00129,-1.91085 -0.95448,-3.69546 -2.54192,-4.75911l-62.85391,-45.72109c-0.98592,-0.72741 -2.17894,-1.11985 -3.40417,-1.11979c-3.16643,0 -5.73333,2.5669 -5.73333,5.73333c-0.00001,0.00747 -0.00001,0.01493 0,0.0224v38.76719l-59.6625,-43.40312c-0.98592,-0.72741 -2.17894,-1.11985 -3.40417,-1.11979z"></path></g></g></svg>
                        </button>
                        <button class="ml-8"><svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                                width="20" height="20"
                                viewBox="0 0 172 172"
                                style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M64.5,10.75v21.5h-37.66699c-8.81836,0 -16.08301,7.26465 -16.08301,16.08301v75.33398c0,8.81836 7.26465,16.08301 16.08301,16.08301h26.91699v-10.75h-26.91699c-3.02344,0 -5.33301,-2.30957 -5.33301,-5.33301v-75.33398c0,-3.02344 2.30957,-5.33301 5.33301,-5.33301h37.66699v21.5l26.875,-26.875zM107.5,32.25v10.75h26.91699c3.02344,0 5.33301,2.30957 5.33301,5.33301v75.33398c0,3.02344 -2.30957,5.33301 -5.33301,5.33301h-37.66699v-21.5l-26.875,26.875l26.875,26.875v-21.5h37.66699c8.81836,0 16.08301,-7.26465 16.08301,-16.08301v-75.33398c0,-8.81836 -7.26465,-16.08301 -16.08301,-16.08301z"></path></g></g></svg></button>
                    </div>
                    <div class="max-w-full mt-3 flex items-center justify-center">
                    <div class="text-xs text-gray-500">1:20</div>
                    <div class="bg-gray-500 rounded-lg w-full xl:w-200 h-1 ml-3"></div>
                    <div class="ml-3 text-xs text-gray-500">4:30</div>
                </div>
            </div>
                
               <div class="volume-controls flex items-center ">
                    <button class="ml-8">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                        width="20" height="20"
                        viewBox="0 0 172 172"
                        style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M155.11354,23.03411l-37.1211,7.95052c-5.28613,1.12947 -9.05911,5.80258 -9.05911,11.20911v65.09349c0,11.17427 -34.4,1.83252 -34.4,33.05625c0,5.73333 3.45604,20.17864 19.8763,20.17864c20.18133,0.00573 25.99036,-15.33398 25.99036,-32.36198v-67.7474l34.85911,-7.64817c3.0788,-0.67653 5.27422,-3.40291 5.27422,-6.56198v-18.7901c0,-2.8552 -2.63339,-4.98039 -5.41979,-4.37839zM22.93333,34.4c-3.1648,0 -5.73333,2.56853 -5.73333,5.73333c0,3.1648 2.56853,5.73333 5.73333,5.73333h68.8c3.1648,0 5.73333,-2.56853 5.73333,-5.73333c0,-3.1648 -2.56853,-5.73333 -5.73333,-5.73333zM22.93333,63.06667c-3.1648,0 -5.73333,2.56853 -5.73333,5.73333c0,3.1648 2.56853,5.73333 5.73333,5.73333h68.8c3.1648,0 5.73333,-2.56853 5.73333,-5.73333c0,-3.1648 -2.56853,-5.73333 -5.73333,-5.73333zM22.93333,91.73333c-3.1648,0 -5.73333,2.56853 -5.73333,5.73333c0,3.1648 2.56853,5.73333 5.73333,5.73333h68.8c3.1648,0 5.73333,-2.56853 5.73333,-5.73333c0,-3.1648 -2.56853,-5.73333 -5.73333,-5.73333zM22.93333,120.4c-3.1648,0 -5.73333,2.56853 -5.73333,5.73333c0,3.1648 2.56853,5.73333 5.73333,5.73333h40.90599c0.83133,-4.51213 2.30668,-8.30187 4.22161,-11.46667z"></path></g></g></svg>
                    </button>

                    <button class="ml-8">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                        width="20" height="20"
                        viewBox="0 0 172 172"
                        style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M0,24.08v110.08h172v-110.08zM6.88,30.96h158.24v96.32h-158.24zM70.95,57.0825c-0.37625,0 -0.73906,0.13438 -1.075,0.3225c-0.68531,0.38969 -1.075,1.15563 -1.075,1.935v43.7525c0,0.77938 0.40313,1.54531 1.075,1.935c0.33594,0.20156 0.69875,0.215 1.075,0.215c0.37625,0 0.84656,-0.01344 1.1825,-0.215l37.84,-21.93c0.67188,-0.38969 1.075,-1.15562 1.075,-1.935c0,-0.77937 -0.40312,-1.43781 -1.075,-1.8275l-37.84,-21.93c-0.33594,-0.18812 -0.80625,-0.3225 -1.1825,-0.3225zM37.195,141.04c-1.89469,0.17469 -3.29219,1.86781 -3.1175,3.7625c0.17469,1.89469 1.86781,3.29219 3.7625,3.1175h96.32c1.23625,0.01344 2.39188,-0.63156 3.02344,-1.70656c0.61813,-1.075 0.61813,-2.39187 0,-3.46687c-0.63156,-1.075 -1.78719,-1.72 -3.02344,-1.70656h-96.32c-0.1075,0 -0.215,0 -0.3225,0c-0.1075,0 -0.215,0 -0.3225,0z"></path></g></g></svg>
                    </button>
                    <button class="ml-8">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                        width="20" height="20"
                        viewBox="0 0 172 172"
                        style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M83.0975,10.32c-1.04812,0 -2.08281,0.215 -3.1175,0.5375c-2.08281,0.65844 -4.07156,1.89469 -5.805,3.655l-40.42,40.42h-23.435c-5.73781,0 -10.4275,4.68969 -10.4275,10.4275v41.28c0,5.73781 4.68969,10.4275 10.4275,10.4275h23.435l40.3125,40.0975c3.84313,3.85656 8.77469,5.54969 12.7925,3.655c4.04469,-1.90812 6.02,-6.50375 6.02,-11.825v-127.28c0,-5.16 -2.63375,-9.44656 -6.665,-10.8575c-1.00781,-0.34937 -2.06937,-0.5375 -3.1175,-0.5375zM83.205,17.2c0.34938,0 0.61813,0.02688 0.86,0.1075c0.98094,0.33594 1.935,1.20938 1.935,4.4075v127.28c0,3.66844 -1.20937,5.30781 -2.0425,5.6975c-0.83312,0.38969 -2.51281,0.43 -5.16,-2.2575l-43.3225,-43.3225c-0.06719,-0.04031 -0.14781,-0.08062 -0.215,-0.1075c0.25531,0.22844 -0.86,-1.94844 -0.86,-3.225v-39.56c0,-1.27656 1.15563,-3.48031 0.86,-3.225c0.08063,-0.06719 0.14781,-0.13437 0.215,-0.215l43.5375,-43.43c1.6125,-1.62594 3.13094,-2.13656 4.1925,-2.15zM10.32,62.0275h17.845c-0.44344,1.31688 -0.645,2.75469 -0.645,4.1925v39.56c0,1.43781 0.215,2.86219 0.645,4.1925h-17.845c-1.85437,0 -3.3325,-1.47812 -3.3325,-3.3325v-41.28c0,-1.85437 1.47813,-3.3325 3.3325,-3.3325zM105.0275,63.3175c-1.66625,0.20156 -2.92937,1.57219 -3.01,3.25188c-0.08062,1.66625 1.04813,3.15781 2.6875,3.52062c7.04125,1.84094 12.255,8.26406 12.255,15.91c0,7.64594 -5.21375,14.06906 -12.255,15.91c-1.84094,0.47031 -2.94281,2.35156 -2.4725,4.1925c0.47031,1.84094 2.35156,2.94281 4.1925,2.4725c10.01094,-2.62031 17.415,-11.78469 17.415,-22.575c0,-10.79031 -7.40406,-19.95469 -17.415,-22.575c-0.45687,-0.13437 -0.92719,-0.16125 -1.3975,-0.1075z"></path></g></g></svg>
                    </button>
                    <div class="bg-gray-500 rounded-lg w-14 h-1 ml-3"></div>
               </div>

            </div>
        </div>
    </div>
</template>

<style>
    .sidebar-spotify::-webkit-scrollbar{
        width: 8px;
        background-color: #121212;
    }
    .sidebar-spotify::-webkit-scrollbar-thumb{
        border-radius: 8px;
        background-color: #535353;
    }
    .content-spotify::-webkit-scrollbar{
        width: 8px;
        background-color: #181818;
    }
    .content-spotify::-webkit-scrollbar-thumb{
        border-radius: 8px;
        background-color: #535353;
    }
</style>