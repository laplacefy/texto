import 'package:flutter/material.dart';

class Pagina_Lista extends StatelessWidget {
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: Padding(
          padding: EdgeInsets.all(80),
          child: Column(children: [
              Row(
                children: [
                  Expanded(
                    child: TextField(
                      decoration: InputDecoration(
                        border: OutlineInputBorder(),
                        labelText: "Adicione uma tarefa",
                        hintText: "Digite aqui",
                        contentPadding: EdgeInsets.symmetric(
                          vertical: 12,
                          horizontal: 16,
                        ),
                      ),
                    ),
                  ),
                  SizedBox(width: 20),
                  ElevatedButton(
                    onPressed: () {},
                    style: ElevatedButton.styleFrom(
                      primary: Color.fromARGB(255, 43, 247, 244),
                      padding: EdgeInsets.all(20),
                    ),
                    child: Icon(
                      Icons.add,
                      size: 30,
                    ),
                  ),
                ], 
              ),
              SizedBox(
                height: 120,
                child: ListView( 
                  


                  children: [
                    
                    ListTile(
                      title: Text("O professor dieimes pega código do chat gpt"),
                      subtitle: Text("Você concorda?"),
                      leading: Icon(Icons.question_mark, size: 30,),
                    ),

                    ListTile(
                      title: Text("O professor dieimes pega código do chat gpt"),
                      subtitle: Text("Você concorda?"),
                      leading: Icon(Icons.question_mark, size: 30,),
                    ),

                    ListTile(
                      title: Text("O professor dieimes pega código do chat gpt"),
                      subtitle: Text("Você concorda?"),
                      leading: Icon(Icons.question_mark, size: 30,),
                    ),

                    ListTile(
                      title: Text("O professor dieimes pega código do chat gpt"),
                      subtitle: Text("Você concorda?"),
                      leading: Icon(Icons.question_mark, size: 30,),
                    ),

                    ListTile(
                      title: Text("O professor dieimes pega código do chat gpt"),
                      subtitle: Text("Você concorda?"),
                      leading: Icon(Icons.question_mark, size: 30,),
                    ),

                  SizedBox(width: 10),
                  ElevatedButton(
                    onPressed: () {},
                    child: Text("limpar"),
              
                      ),
                    ],
                   ),
                  ),
                 ],
                ),
              ),
            ),
          );
        }
      }
