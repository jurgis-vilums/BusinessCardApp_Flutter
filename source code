import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home:JurgisApp()
  ));
}

class JurgisApp extends StatefulWidget {
  const JurgisApp({Key key}) : super(key: key);

  @override
  _JurgisAppState createState() => _JurgisAppState();
}

class _JurgisAppState extends State<JurgisApp> {
  int counter =1;
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      floatingActionButton: FloatingActionButton(onPressed: () {
        setState(() {
          counter+=1;
        });
      },
      backgroundColor: Colors.amberAccent,
        child: Icon(Icons.add, color: Colors.grey[800],),
      
      ),
      backgroundColor: Colors.grey[900],
      appBar: AppBar(
        title: Text("JurgisApp"),
        centerTitle: true,
        backgroundColor: Colors.grey[800],
        elevation: 0,
        
      ),
      body: Padding(
      padding: EdgeInsets.fromLTRB(40.0, 80.0, 40.0, 0.0),

        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Center(
              child: CircleAvatar(
                backgroundImage: AssetImage("assets/bird.png"),
                radius: 50,
              ),
            ),
            Divider(height: 50,color: Colors.grey[600],),
            Text("NAME",
            style: TextStyle(
              color: Colors.grey,
              letterSpacing: 2,
              fontSize:15,
            ),
            ),

            SizedBox(height: 5),
            Text("Jurģis Viļums",
              style: TextStyle(
                  color: Colors.amberAccent,
                  letterSpacing: 2,
                  fontSize:30,
                  fontWeight: FontWeight.bold

              ),
            ),
            SizedBox(height: 30,),
            Text("PHONE NUMBER",
              style: TextStyle(
                  color: Colors.grey,
                  letterSpacing: 2,
                  fontSize:15,

              ),
            ),

            SizedBox(height: 5),
            Text("27803767",
              style: TextStyle(
                  color: Colors.amberAccent,
                  letterSpacing: 1,
                  fontSize:30,
                  fontWeight: FontWeight.bold

              ),
            ),
            SizedBox(height: 30,),
            Row(
              children: [
                Icon(Icons.email, color: Colors.grey,),
                SizedBox(width: 10),
                Text("vilumsjurgis.lv@gmail.com", style: TextStyle(color: Colors.grey, fontSize: 20.0),),

              ],
            ),

            SizedBox(height: 30,),
            Text("AGE",
              style: TextStyle(
                  color: Colors.grey,
                  letterSpacing: 2,
                  fontSize:15,

              ),
            ),

            SizedBox(height: 5),
            Text("$counter",
              style: TextStyle(
                  color: Colors.amberAccent,
                  letterSpacing: 1,
                  fontSize:35,
                  fontWeight: FontWeight.bold
              ),
            ),

          ],
        ),
        
      ),
    );
  }
}

