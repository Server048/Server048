### Hi there 👋

<!--
**Server048/Server048** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
        
        
      .animate-image {
        animation: image-transition 2s ease-in-out
      }
      .animate-transition {
        animation: transition-animate 2s ease-in-out;
      }
      @keyframes transition-animate {
        0% {
          transform: translateX(-300px);
        }
        100% {
          transform: translateX(0px);
        }
      }
      @keyframes image-transition {
        0% {
          transform: translateX(300px);
        }
        100% {
          transform: translateX(0px);
        }
      }
      .font-monserrat700 {
        font-family: 'Montserrat', sans-serif;
        font-weight: bold;
        color: undefined;
      }
      .font-monserratRegular {
        font-family: 'Montserrat', sans-serif;
        color: undefined;
      }
      .card-wrapper {
        background: #ecf0f1;
        background-image: url('data:image/svg+xml,%3Csvg%20width%3D%2264%22%20height%3D%2264%22%20viewBox%3D%220%200%2064%2064%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%3Ctitle%3Etic-tac-toe%3C%2Ftitle%3E%3Cpath%20d%3D%22M8%2016c4.418%200%208-3.582%208-8s-3.582-8-8-8-8%203.582-8%208%203.582%208%208%208zm0-2c3.314%200%206-2.686%206-6s-2.686-6-6-6-6%202.686-6%206%202.686%206%206%206zm33.414-6l5.95-5.95L45.95.636%2040%206.586%2034.05.636%2032.636%202.05%2038.586%208l-5.95%205.95%201.414%201.414L40%209.414l5.95%205.95%201.414-1.414L41.414%208zM40%2048c4.418%200%208-3.582%208-8s-3.582-8-8-8-8%203.582-8%208%203.582%208%208%208zm0-2c3.314%200%206-2.686%206-6s-2.686-6-6-6-6%202.686-6%206%202.686%206%206%206zM9.414%2040l5.95-5.95-1.414-1.414L8%2038.586l-5.95-5.95L.636%2034.05%206.586%2040l-5.95%205.95%201.414%201.414L8%2041.414l5.95%205.95%201.414-1.414L9.414%2040z%22%20fill%3D%22%23eaeaea%22%20fill-opacity%3D%22undefined%22%20fill-rule%3D%22evenodd%22%2F%3E%3C%2Fsvg%3E');
        width: 640px !important;
        height: 320px !important;
        margin: 0;
        box-sizing: border-box;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding: 5%;
      }
      p{
        font-size: .8rem;
        margin-top: -4px;
      }
      p.site {
        margin-top: 10px;
      }
      .card-img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        object-fit: cover;
        transition: all .3s ease;
      }
      .card-wrapper-desc {
        display: flex; 
        flex-direction: column;
        width: 70%;
      }
      .card-wrapper-img {
        display:block;
        padding-top: 8px;
        margin: 2%;
      }
      .card-icon {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        font-size: 11px;
        position: absolute;
        bottom: 10px;;
        right: 150px;
        width: 100%;
      }
      div.line{
        width: 0%;
        min-width: 100%;
        max-width: 100%;
        margin: 0 auto;
        border: none;
        border-bottom: 1px solid #666;
      
