# Pratica_LR
Pratica de laços de repetição
//exercicio 1

void main() {
  int numero = 0;
  String rest = "0";
  
  for(int i = 1; i<=100; i++) {
    rest += " ${i + 0}";
    
    
    print("$rest");
  }
}


//exercicio 2

void main() {
  
  int maior = 9872;
 
  const List numero = [10, 20, 30, 100, 400,1503, 9873, 8, 9, 12];
  
    for(int num in numero){
      if(num > maior){
        maior = num;
        print("O maior índice é: $maior");
    }
  }
}
