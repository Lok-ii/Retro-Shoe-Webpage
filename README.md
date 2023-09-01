# Retro-Shoe-Webpage

<h4># Hosted Link:- https://lok-ii.github.io/Retro-Shoe-Webpage/dist/index.html</h4>
<br>
<br>

# Description:


![Screenshot 2023-09-01 114515](https://github.com/Lok-ii/Retro-Shoe-Webpage/assets/129180844/904c6c4d-009d-464b-a5d9-468ddb1e871f)
![Screenshot 2023-09-01 114529](https://github.com/Lok-ii/Retro-Shoe-Webpage/assets/129180844/102804e1-6b84-417d-8533-b6c9bcaecf1e)

    Main Section:

        <section class="font-mono flex items-center w-full h-screen justify-center">: Defines a section that takes up the entire viewport and centers its content both horizontally and vertically. It uses a monospaced font for its text.
        
    Main Container:
        
        <div class="main-container container max-w-xl h-[80%] sm:h-72 relative shadow-2xl">: This is a container that holds most of the page's content.
            container: Limits the width of the content.
            max-w-xl: Sets the maximum width for larger screens.
            h-[80%] sm:h-72: Sets the height of the container as a percentage of the screen height, with different values for small screens.
            relative: Allows child elements to be positioned relative to this container.
            shadow-2xl: Adds a shadow effect to the container.
        
    Shoe Image Container:
        
        <div class="shoe w-[90%] h-[30%] sm:w-[30%] sm:h-[80%] absolute flex items-center justify-center overflow-hidden top-4 left-6 bg-center">: This container holds an image of a retro shoe.
            w-[90%] h-[30%]: Sets the width and height as percentages of the parent container.
            sm:w-[30%] sm:h-[80%]: Adjusts the width and height for small screens.
            absolute: Positions the container absolutely within its parent.
            flex items-center justify-center: Centers the image both horizontally and vertically.
            overflow-hidden: Clips any overflowing content within the container.
            top-4 left-6: Positions the container 4 units from the top and 6 units from the left within its parent.
            bg-center: Centers the background image.
        
    Product Information Container:
        
        <div class="bg-black text-white font-bold flex flex-col px-8 items-start sm:items-center sm:justify-center justify-end h-2/4 sm:h-[35%] w-full gap-2">: This container displays product information.
            bg-black text-white: Sets the background color to black and the text color to white.
            font-bold: Applies a bold font-weight to the text.
            flex flex-col: Arranges child elements in a column layout.
            px-8: Adds horizontal padding.
            items-start sm:items-center sm:justify-center: Aligns items to the start for small screens and centers them for larger screens.
            justify-end: Aligns items to the end (bottom) of the container.
            h-2/4 sm:h-[35%]: Sets the height of the container as a percentage of its parent, with different values for small screens.
            w-full: Sets the width to 100%.
            gap-2: Adds vertical spacing between child elements.
        
    Size Selection Container:
        
        <div class="bg-white w-full flex flex-col items-start sm:items-end justify-center h-2/4 sm:h-[65%]">: This container holds size selection options.
            bg-white: Sets the background color to white.
            w-full: Sets the width to 100%.
            flex flex-col: Arranges child elements in a column layout.
            items-start sm:items-end: Aligns items to the start for small screens and to the end for larger screens.
            justify-center: Centers child elements vertically.
            h-2/4 sm:h-[65%]: Sets the height as a percentage of its parent, with different values for small screens.
        
    Size Options:
        
        <div class="flex text-black py-4 px-4 sm:pr-24 gap-4">: These are buttons for selecting different sizes.
            flex: Arranges buttons in a row layout.
            text-black: Sets the text color to black.
            py-4 px-4 sm:pr-24 gap-4: Adds padding and spacing between buttons. Adjusts padding for small screens.
        
    Action Buttons and Wishlist Icon:
        
        <div class="px-4 sm:pr-8 w-full flex gap-4 items-center flex-wrap sm:flex-nowrap justify-start sm:justify-end">: These are buttons for actions like "BUY NOW" and "ADD TO BAG," along with a wishlist (heart) icon.
            px-4 sm:pr-8: Adds horizontal padding. Adjusts padding for small screens.
            w-full: Sets the width to 100%.
            flex gap-4: Arranges buttons with spacing in between.
            items-center: Centers items vertically.
            flex-wrap sm:flex-nowrap: Allows wrapping of buttons for small screens but keeps them in a single line for larger screens.
            justify-start sm:justify-end: Aligns buttons to the start for large screens and to the end for small screens.
        
    Shipping Information:
        
        <p class="text-xs sm:text-sm text-gray-400 p-4">: Provides information about free shipping.
            text-xs sm:text-sm: Sets the text size for small and larger screens.
            text-gray-400: Sets the text color to a shade of gray.
            p-4: Adds padding around the paragraph.
