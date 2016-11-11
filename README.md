# t1-compiladores2

// 1- Compilar Arquivo Antlr:
java -jar antlr-4.5.2-complete.jar Hello.g4
// 2- Compilar Arquivos Java gerados:
javac -cp antlr-4.5.2-complete.jar Hello*.java
// 3- Rodar Analisador Léxico/Sintático:
java -cp .;antlr-4.5.2-complete.jar org.antlr.v4.runtime.misc.TestRig Hello r -tree
java -cp .;antlr-4.5.2-complete.jar org.antlr.v4.runtime.misc.TestRig Hello r -gui
