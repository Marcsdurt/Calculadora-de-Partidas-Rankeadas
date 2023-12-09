function determineHeroLevel(victories, defeats){
    let rankedBalance = victories - defeats
    let levelTitle
    switch (true){
      case victories <= 10:
      levelTitle = "Ferro"
      break
      case victories >= 11 && victories <= 20:
      levelTitle = "Bronze"
      break
       case victories >= 21 && victories <= 50:
      levelTitle = "Prata"
      break
       case victories >= 51 && victories <= 80:
      levelTitle = "Ouro"
      break
       case victories >= 81 && victories <= 90:
      levelTitle = "Diamante"
      break
       case victories >= 91 && victories <= 100:
      levelTitle = "Lendário"
      break
      default:
      levelTitle = "Imortal"
    }
  
    return ("O Héroi tem saldo de "+rankedBalance+" está no nível "+levelTitle)
}

let message = determineHeroLevel(8, 2)
console.log(message)
