var inter = 0;
var intervalo = setInterval(function(){
  var imgSrcs = document.getElementsByClassName('FFVAD');
  window.scrollBy(0,400);
  for(i = 0; i < imgSrcs.length; i++){
    if(imgSrcs[i].src.indexOf('5F51A481') !== -1){ // nesta linha, substituir o valor 5F51A481 pelo correspondente o id da sua imagem no instagram, eu usei o parâmetro oe= do instagram quando inspecionado para escolher as fotos a serem deletadas
      imgSrcs[i].parentNode.parentNode.parentNode.parentNode.parentNode.childNodes[1].childNodes[0].click();
      var intervalo1 = setTimeout(function(){
        console.log(document.getElementsByClassName('pbNvD  fPMEg   ')[0].childNodes[0].childNodes[0].childNodes[0].childNodes[0].click());
      },1000);
     var intervalo2 = setTimeout(function(){
       document.getElementsByClassName('aOOlW -Cab_   ')[0].click();
     },1500);
     inter++;
     console.log(inter + ' Fotos encontradas foram apagadas');
     if(inter == 10){ // aqui coloco manualmente(por enquanto) a quantidade de fotos que iremos apagar, para podermos limpar o intervalo
      clearInterval(intervalo);
      console.log('Intervalo Limpo com ' + inter + ' fotos apagadas...');
     }
    }
  }
  console.log('rodando o intervalo...');
},3000);
