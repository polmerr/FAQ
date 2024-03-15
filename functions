function revealText (x=''){
    allText = document.querySelectorAll('.text')
    allImages = document.querySelector("#questions").querySelectorAll('img')
    hideText = true;
    question = document.querySelector('#question' + x );
    hiddenText = question.querySelector('.text')
    image = question.querySelector('img')
    if(hiddenText.hidden === true)
    {
        hideText=false;
        
    }
    else{
        hideText = true;
        
    }
    
    for(let i=0; i<allText.length; i++)
    {
        allText[i].hidden = true;
        allImages[i].setAttribute('src', 'assets/images/plus.png');
    }
    
    if(hideText===false)
    {
        image.setAttribute('src', 'assets/images/minus.png');
    }
    hiddenText.hidden = hideText;
    console.log(allText);
    
}
