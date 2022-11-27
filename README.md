# Atividade-GCC132
 Criar seu primeiro programa em c++ é bem símples, e pode ser feito em poucos passos:

* Crie um novo arquivo com o nome "hello.cpp"
* Abra o arquivo com o editor de texto de sua preferência, e insira o seguinte código:
  ```
  #include <iostream>

  int main() {
      std::cout << "Hello World!";
      return 0;
  }
  ```
* Após salvar o arquivo, abra seu terminal na pasta onde o arquivo foi salvo e insira os seguintes comandos para compilar e executar o programa:
  ```
  g++ -o hello.out hello.cpp
  ./hello.out
  ```
