

<template>
   <body>
      <h1 class="font-extrabold">learning tailwind(without vue)</h1><!--  viem ze toto by malo byt v main ale chcem mat na main ten flex a inak to vyzera zle a nechcem to cele prerabat -->
      <main class="flex h-screen bg-gradient-to-r from-cyan-100 to-blue-600 overflow-x-scroll"> 
         <div class="flex items-start w-screen p-10 overflow-x-scroll">
            <section class="flex-shrink-0 w-80 mx-4 p-3 bg-blue-300 rounded-lg">
               <header>
                  <h3 class="font-bold p-2">FIRST LIST</h3>
               </header>

               <ul>
                  <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                  <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                  <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                  <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
               </ul>

               <footer>
                  <a class="text-gray-700 block hover:bg-blue-200 p-2 rounded-md" href="">
                     Add a card...
                  </a>
               </footer>
               <form action="">
                        <textarea class="outline-none w-full shadow-inner" rows="3"></textarea>
                        <div class="my-1.5 flex items-center">
                           <button class="bg-green-500 font-semibold hover:bg-green-400 rounded text-white p-2">
                              Add card
                           </button>
                           <button class="text-gray-500 hover:text-gray-700">
                              <svg class="fill-current w-6 h-6 ml-3" viewBox="0 0 1024 1024" xmlns="http://www.w3.org/2000/svg">
                                 <path d="M195.2 195.2a64 64 0 0 1 90.496 0L512 421.504 738.304 195.2a64 64 0 0 1 90.496 90.496L602.496 512 828.8 738.304a64 64 0 0 1-90.496 90.496L512 602.496 285.696 828.8a64 64 0 0 1-90.496-90.496L421.504 512 195.2 285.696a64 64 0 0 1 0-90.496z"/>
                              </svg>
                           </button>   
                        </div>
                     </form>
            </section>

            <section class="h-full flex-shrink-0 w-80 mx-4 p-3 bg-blue-300 rounded-lg">
               <div class="h-full overflow-y-scroll">
                  <header>
                        <h3 class="font-bold">SECOND LIST</h3>
                  </header>
                  <ul>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer leading-loose">
                        <span class="font-bold">Leading-loose</span> dolor sit amet consectetur adipisicing elit. Aliquid veniam enim rerum voluptatibus assumenda qui nisi asperiores
                        reprehenderit tempore necessitatibus autem dolore tempora iste eaque repudiandae, suscipit aliquam molestias quo?
                     </li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>   
                  </ul>

                  <footer>
                     <a class="text-gray-700 block hover:bg-blue-200 p-2 rounded-md" href="">
                        Add a card...
                     </a>
                  </footer>
               </div>   
            </section>
            <section class="flex-shrink-0 w-80 mx-4 p-3 bg-blue-300 rounded-lg">
                  <header>
                        <h3 class="font-bold">SECOND LIST</h3>
                  </header>

                  <ul>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                  </ul>

                  <footer>

                  </footer>
               </section>
               <section class="flex-shrink-0 w-80 mx-4 p-3 bg-blue-300 rounded-lg">
                  <header>
                        <h3 class="font-bold">SECOND LIST</h3>
                  </header>

                  <ul>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                     <li class="bg-white my-1 p-3 rounded-lg border-b border-gray-400 hover:bg-gray-200 cursor-pointer">something</li>
                  </ul>

                  <footer>

                  </footer>
               </section>
         </div>
      </main>





      <main class= "h-screen bg-gray-900">
         <div class="p-10">
            <div>  
               <header>
                  <h2 class="p2 text-3xl text-blue-500 font-semibold">Tasks</h2>
               </header>
            </div> 

            <div>
               <ul>
                  <li @click="changeColorDone()" :style="{backgroundColor: bgColor}" class="text-left bg-gray-800 my-1 p-3 rounded-lg border-b border-gray-900 hover:bg-gray-700 cursor-pointer w-full text-white" v-for="task in tasks">
                     {{ task.text }}
                  </li>
               </ul>
            </div>   

            
            <footer class=" text-left block bg-gray-800 my-1 p-3 rounded-lg border-b border-gray-900 hover:bg-gray-700 cursor-pointer w-full">
               <a class="text-blue-500 block" @click="showModal=true">Add a task</a>
               <div v-if="showModal" class="">
                  <div class="text-center flex">
                     <textarea class="bg-gray-800 text-white mx-5" v-model="newTask" name="task" id="task" cols="30" rows="1"></textarea>
                     <div>
                        <button class="text-center bg-blue-500 m-2 p-2 rounded-md" @click="addTask()">Add</button>
                        <button class="text-center bg-blue-500 m-2 p-2 rounded-md" @click="showModal = false">Close</button>
                     </div>   
                  </div>
               </div>
            </footer>
            
         </div>
      </main>
   </body>
</template>

<script>
export default {
   data(){
      return{
         showModal: false,
         newTask: "",
         tasks: [],
         bgColor: "gray-800"
      }
   },
   methods: {
      addTask(){
         this.tasks.push({
            text: this.newTask,
         })
         this.showModal = false
         this.newTask = ""
      },
      changeColorDone(){
         this.bgColor = "green"
      },
   },
}
</script>

