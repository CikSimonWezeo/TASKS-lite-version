

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





      <main class= "h-screen bg-gray-700">
         <div class="p-10">
            <div class="">  
               <header class="flex items-center">
                  <div class="text-blue-500 pr-2">
                     <svg class="w-8 h-8 fill-current" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path class="fill-current" d="M10.55 2.53c.84-.7 2.06-.7 2.9 0l6.75 5.7c.5.42.8 1.05.8 1.71v9.8c0 .97-.78 1.76-1.75 1.76h-3.5c-.97 0-1.75-.79-1.75-1.75v-5.5a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25v5.5c0 .96-.78 1.75-1.75 1.75h-3.5C3.78 21.5 3 20.7 3 19.75v-9.8c0-.67.3-1.3.8-1.73l6.75-5.69zm1.93 1.15a.75.75 0 00-.96 0l-6.75 5.7a.75.75 0 00-.27.56v9.8c0 .14.11.26.25.26h3.5c.14 0 .25-.12.25-.25v-5.5c0-.97.78-1.75 1.75-1.75h3.5c.97 0 1.75.78 1.75 1.75v5.5c0 .13.11.25.25.25h3.5c.14 0 .25-.12.25-.25v-9.8c0-.23-.1-.44-.27-.58l-6.75-5.7z" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                     </svg>
                  </div>
                  <div>
                     <h2 class="p2 text-3xl text-blue-500 font-semibold">Tasks</h2>
                  </div>
               </header>
            </div>
            <div class="overflow-x-scroll"> 
               <div class="flex mb-5">
                  <div class="w-1/5 bg-gray-900 p-2 rounded-md mr-2 mt-5 flex-shrink-0" v-for="col in cols" :key="col">
                     <div>
                        <h2 contenteditable="" class="text-left mx-1 cursor-pointer hover:bg-gray-700 rounded-md text-blue-500 text-lg font-bold">{{ col }}</h2>
                     </div>
                     <ul>
                        <li @click="changeColorDone()" :style="{backgroundColor: bgColor}" class="text-left bg-gray-800 my-2 p-3 rounded-lg border-b border-gray-700 hover:bg-gray-700 cursor-pointer w-full text-white" v-for="task in tasks" :key="task.id">
                           {{ task.text }}
                        </li>
                     </ul>
                     <div class=" text-left block my-1 p-3 rounded-lg border-b border-gray-900 hover:bg-gray-700 cursor-pointer w-full"> 
                        <a class="text-blue-500 block" @click="showModal = true">Add a task</a>
                        <div v-if="showModal" class="">
                           <div class="text-center flex">
                              <textarea class="bg-gray-800 text-white mx-5 p-2" v-model="newTask" name="task" id="task" cols="30" rows="1"></textarea>
                              <div>
                                 <button class="text-center bg-blue-500 m-2 p-2 rounded-md" @click="addTask()">Add</button>
                                 <button class="text-center bg-blue-500 m-2 p-2 rounded-md" @click="showModal = false">Close</button>
                              </div>   
                           </div>
                        </div>
                     </div>     
                  </div>
               </div>
            </div>   
            <div class="fotn-bold flex my-5">
               <input class="rounded-xl p-2 mr-2 hover:bg-gray-200" placeholder="name of new column" v-model="newColumnName">
               <div @click="addNewCol()" class="bg-blue-500 rounded-xl hover:cursor-pointer hover:bg-blue-400 p-2 text-xl font-semibold">Add</div>
            </div>    
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
         bgColor: "gray-800",
         cols: ["My Day", "Important", "Planned", "Assigned to me", "Tasks"],
         newColumnName: ""
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
      addNewCol(){
         this.cols.push(this.newColumnName);
         this.newColumnName = "";
      }
   },
}
</script>

