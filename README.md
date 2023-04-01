# Projeto de Computação grafica
**Alunos**
- Felipe Carvalho Godoi
- Pedro Henrique Maciel Alves
- Pedro Henrique dos Santos M.
- Jhonatan Gardioli Lourenco
- Thallys Henrique Martins

**Professora**
- Ana Paula Piovesan Melchiori

## Requisitos do projeto
- [x] Quarto
  - [x] Parede, Chão, Teto
  - [x] Porta, Janela 
- [x] Objetos
  - [x] Cama, tapete, mesa, quadros, entre outros
- [x] Objetos dinamicos
  - [x] Helice do ventilador
- [x] Ambiente
  - [x] Iluminacão
  - [x] Animacão de objetos
- [ ] Navegacão
  - [x] Mouse, teclado
  - [ ] Colisão
  - [ ] Fisica(gravidade)
  - [ ] Selecão de objetos


## Requisitos para executar o projeto
- Instale a OpenGL Utility Toolkit (GLUT)
- Instale o pacote Miscellaneous Mesa GL utilities
- Instale as bibliotecas X11 miscellaneous utility library e X11 Input extension library
- Instale a GLFW3 (OpenGL Framework Window) 
- Instale a biblioteca **ljpeg** para codificação e decodificação de imagens JPEG

## Codigo de compilação e execução
- Compile o codigo 
```
> g++ main.cpp bibutil.cpp bibutilNoTex.cpp -o main -lGL -lGLU -lglut -lglfw -ljpeg
```

- Execute
```
> ./main
```

