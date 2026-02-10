🚀 BetaCalculator DLL
A BetaCalculator é uma biblioteca desenvolvida em C# projetada para realizar cálculos de subtração totalitária, garantindo que o resíduo final da operação seja sempre zero. É a ferramenta ideal para quando você precisa que "não sobre nada para o betinha".

🛠️ Instalação
Para utilizar a DLL, adicione a referência do arquivo BetaCalculator.dll ao seu projeto .NET.

💻 Como Usar
A classe principal funciona de forma instanciada. O método Beta processa um valor inteiro e retorna o resultado da subtração do valor por ele mesmo.

C#
using BetaCalculatorSystem;

// 1. Instancie a classe
var calculator = new BetaCalculator();

// 2. Chame o método passando o valor desejado (int)
int resultado = calculator.Beta(100); 

// Resultado: 0 (100 - 100)
Console.WriteLine($"Sobrou para o betinha: {resultado}");
