<template>
    <div class="backimage">
     
    
    </div>
  </template>
  <script>


  export default {
  
    data() {
        return {
            isOpen: false,
            active: 'register',
            
        };
    },
    methods: {
      
        }
    }
    


  </script>
  <style>
  /* .btn_group{
    
  } */
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

 
  
.backimage{
  /* background-size: contain;
  background-repeat: no-repeat;
  width: 200px; */
  height: 90vh;
background-image:url(../assets/img/BG1.png) ;

  }
  /* Style buttons */
.btn {
  margin: auto;
  top: 5%;
  position: relative;
    height: 2rem;
    width: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    
    font-size: 1.1rem;
    padding: 1.8rem 15rem;
    font-weight: 600;
    user-select: none;
    border-radius: 4px;
}

ul {
  list-style-type: none;
  padding: 10px;
}


  </style>