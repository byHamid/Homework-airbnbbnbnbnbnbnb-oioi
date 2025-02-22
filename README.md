<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://unpkg.com/@tailwindcss/browser@4"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="shortcut icon" href="./airbnblogo.png" type="image/x-icon">
    <title>Airbnb | Vacation rentals, cabins, beach houses, & more</title>
</head>
<body class="p-6 sm: flex flex-col">
    <!-- Header -->
    
    <header class="flex justify-between items-center text-center mx-7" >        
        <div class="text-red-500  font-bold flex items-center text-2xl">
            <i class="fa-brands fa-airbnb text-4xl"></i>airbnb
        </div>
        <nav class="flex space-x-6 text-gray-600 text-xl">
            <a href="#" class="font-semibold text-black hover:bg-gray-100 p-3 rounded-full">Home</a>
            <a href="#" class="hover:bg-gray-100 p-3 rounded-full">Experiences</a>
        </nav>

        <div class="flex items-center space-x-4">
            <a href="#" class="font-semibold hover:bg-gray-100 p-3 rounded-full" >Airbnb your home</a>
            <button class="p-2 rounded-full hover:bg-gray-100">
                <i class="fa-solid fa-globe"></i>
            </button>
            <button class="flex items-center border p-3 rounded-full hover:shadow-lg">
                <span class="mr-2"><i class="fa-solid fa-bars"></i></span>
                <span class="w-6 h-6 bg-gray-500 rounded-full text-white">
                    <i class="fa-solid fa-user"></i>
                </span>
            </button>
        </div>
    </header>
    <div class="flex items-center justify-center bg-white shadow-lg rounded-full p-2 w-full max-w-3xl px-[456px]">
        <!-- Destination -->
        <div class="flex flex-col flex-1 px-4 border-r">
            <label class="text-xs font-semibold text-gray-700">Where</label>
            <input type="text" placeholder="Search destinations" class="bg-transparent focus:outline-none text-sm text-gray-600">
        </div>

        <!-- Check-in -->   
        <div class="flex flex-col flex-1 px-4 border-r py-[10px] ">
            <label class="text-xs font-semibold text-gray-700">Check in</label>
            <input type="text" placeholder="Add dates" class="bg-transparent focus:outline-none text-sm text-gray-600">
        </div>

        <!-- Check-out -->
        <div class="flex flex-col flex-1 px-4 border-r">
            <label class="text-xs font-semibold text-gray-700">Check out</label>
            <input type="text" placeholder="Add dates" class="bg-transparent focus:outline-none text-sm text-gray-600">
        </div>

        <!-- Guests -->
        <div class="flex flex-col flex-1 px-4">
            <label class="text-xs font-semibold text-gray-700">Who</label>
            <input type="number" placeholder="Add guests" class="bg-transparent focus:outline-none text-sm text-gray-600">
        </div>

        <!-- Search Button -->
        <button class="bg-red-500 text-white p-3 rounded-full ml-2 hover:bg-pink-600 transition">
            <i class="fa-solid fa-magnifying-glass"></i>
        </button>
    </div>
<br><br><hr>
    <section class="flex justify-center items-center p-9 ">
        <div class="flex gap-7 text-gray-500 items-center">
            <i class="fa-solid fa-sailboat hover:text-black"></i>
            <i class="fa-solid fa-tree hover:text-black"></i>
            <i class="fa-solid fa-house hover:text-black"></i>

            <div class="text-base justify-around flex">
                <h1 class="border border-gray-200 text-black p-3 rounded-lg hover:border-black hover:bg-gray-200"><i
                        class="fa-solid fa-sliders"></i>Filters</h1>
            </div>  
            <div>
                <h1 class="border border-gray-200 p-3 rounded-lg text-black hover:border-black">Display total before taxes</h1>
            </div>
    </section>
    <div class="flex justify-center gap-[20px] p[20px] grid grid-cols-1 sm:grid-cols-2 sm:items-center lg:grid-cols-4 gap-6">
        <div class="bg-white p-[10px] rounded-xl w-[330px] text-center ">
            <img src="./batumi.avif"class="w-[100%] h-[250px] rounded-xl" alt="">
            <p>Batumi, Georgia <br>1,513 kilometres away <br>Jul 12-17<br>$681 night</p>
        </div>

        <div class="bg-white p-[10px] rounded-xl w-[330px] text-center ">
            <img src="./batumi.avif" class="w-[100%] h-[250px] rounded-xl" alt="">
            <p>Batumi, Georgia <br>1,513 kilometres away <br>Jul 12-17<br>$681 night</p>
        </div>

        <div class="bg-white p-[10px] rounded-xl w-[330px] text-center">
            <img src="./batumi.avif" class="w-[100%] h-[250px] rounded-xl" alt="">
            <p>Batumi, Georgia <br>1,513 kilometres away <br>Jul 12-17<br>$681 night</p>
        </div>
        <div class="bg-white p-[10px] rounded-xl w-[330px] text-center">
            <img src="./batumi.avif" class="w-[100%] h-[250px] rounded-xl" alt="">
            <p>Batumi, Georgia <br>1,513 kilometres away <br>Jul 12-17<br>$681 night</p>
        </div>
    </div>
    <br>
    <div class="bg-gray-100">
        <br><br><hr><br><br>
        <h1 class="text-2xl px-[50px] font-semibold">Inspiration for future getaways</h1><br><br>
        <div class="">
            <span class="font-semibold">Support</span><br><br>Help Center <br>AirCover <br>Anti-discrimination <br> Disability support<br> Cancellation options <br> Report neighborhood concern

        </div><br><hr><br>
        <div class="px-[50px]">© 2025 Airbnb, Inc. · Terms Sitemap · Privacy Your · Privacy Choices</div>
    </div>
    
    
</body>
</html>
