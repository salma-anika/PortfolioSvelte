
<div id="signup" class="w-full h-screen pt-36 grid md:grid-cols-2 w-full  sm:grid-cols-1 bg-slate-300 px-8 py-16">
   <!--
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/forms'),
    ],
  }
  ```
-->

      <div class="mt-5 md:col-span-2 md:mt-0 ">
        <form action="#" method="POST" class="w-1/2 mx-auto pt-36">
          <div class="overflow-hidden shadow sm:rounded-md">
            <div class="bg-white px-4 py-5 sm:p-6">
                <h1 class="font-bold" style="font-size:32px;  font-family:  Helvetica, Arial, sans-serif;"> Signup</h1>
                <h6 class="pb-2">It's easy and quick</h6>
               
                <hr>
              <div class="grid grid-cols-6 gap-6 pt-2">
                <div class="col-span-6 sm:col-span-3">
                  
                  <input type="text" name="first-name" id="first-name" placeholder="First name" autocomplete="given-name" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6 sm:col-span-3">
              
                  <input type="text" name="last-name" id="last-name" placeholder="Surname" autocomplete="family-name" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6 sm:col-span-4">
                
                  <input type="text" name="email-address" id="email-address" placeholder="Mobile number or email address" autocomplete="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6">
                
                  <input type="text" name="street-address" id="street-address" placeholder="Password" autocomplete="street-address" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6  ">
                    <label for="street-address" class="block text-sm font-medium text-gray-700"> Gender</label>
                    <div class="col-span-6 flex ">
                    <div class=" col-span-6 sm:col-span-6 lg:col-span-2 px-1">
                        <input class="form-check-input" type="radio" id="inlineCheckbox1" value="option1">
                        <label class="form-check-label" for="inlineCheckbox1">Male</label>
                      </div>
                      <div class=" col-span-6 sm:col-span-6 lg:col-span-2 px-1">
                        <input class="form-check-input" type="radio" id="inlineCheckbox2" value="option2">
                        <label class="form-check-label" for="inlineCheckbox2">Female</label>
                      </div>
                      <div class=" col-span-6 sm:col-span-6 lg:col-span-2 px-1">
                        <input class="form-check-input" type="radio" id="inlineCheckbox2" value="option2">
                        <label class="form-check-label" for="inlineCheckbox2">Custom</label>
                      </div>
                  </div>
              </div>
              <div class="flex col-span-6 sm:col-span-6 lg:col-span-2">
                <label for="city" class="block text-sm font-medium text-gray-700">City</label>
                
                <input type="day" name="postal-code" id="postal-code" autocomplete="day" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                <input type="month" name="postal-code" id="postal-code" autocomplete="month" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                <input type="year" name="city" id="city" autocomplete="year" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
              </div>

            
            </div>
            <div class="bg-gray-50 px-4 py-3 text-right sm:px-6">
              <button type="submit" class="inline-flex justify-center rounded-md border border-transparent bg-indigo-600 py-2 px-4 text-sm font-medium text-white shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">Save</button>
            </div>
          </div>
        </form>
      </div>
    
  
 
  
  
  
	</div>

