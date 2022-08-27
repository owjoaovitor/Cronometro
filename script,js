const iniciar = document.querySelector('.iniciar')
const pausar =  document.querySelector('.pausar')
const tempo =   document.querySelector('.tempo')
const reset =   document.querySelector('.reset')

iniciar.addEventListener('click', initTempo);
pausar.addEventListener('click', breakTempo);
reset.addEventListener('dblclick', resetTempo);

let i =0;
let timer;

function initTempo() {
 timer = setInterval (() => {
    tempo.innerText = i++;
 }, 199);
    
     /* 'disabled','' (comando desabilita o iniciar depois de apertado. ) */
}

function breakTempo() {
 clearInterval(timer);

}
function resetTempo() { 
   tempo.innerText = 0;
   i = 0;
   
}

