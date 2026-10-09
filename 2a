import 'package:flutter/material.dart';

void main() {
  runApp(MyFullWidgetDemo());
}

class MyFullWidgetDemo extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Widget Showcase',
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(
          title: Text('Widget Demo AppBar'),
          backgroundColor: Colors.purple,
        ),
        body: SingleChildScrollView(
          padding: EdgeInsets.all(16),
          child: Column(
            crossAxisAlignment: CrossAxisAlignment.stretch,
            children: [
              Container(
                color: Colors.lightBlue[100],
                padding: EdgeInsets.all(10),
                child: Image.network(
                  'https://images.pexels.com/photos/674010/pexels-photo674010.jpeg?cs=srgb&dl=pexels-anjana-c-169994674010.jpg&fm=jpg',
                  height: 150,
                  fit: BoxFit.contain,
                ),
              ),
              SizedBox(height: 16),
              Container(
                color: Colors.yellow[200],
                padding: EdgeInsets.all(16),
                child: Center(
                  child: Text(
                    'Hello from Flutter!',
                    style: TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
                    textAlign: TextAlign.center,
                  ),
                ),
              ),
              SizedBox(height: 16),
              Container(
                margin: EdgeInsets.symmetric(vertical: 10),
                padding: EdgeInsets.all(16),
                color: Colors.green[200],
                child: Text(
                  'This is a container with margin and padding',
                  style: TextStyle(fontSize: 18),
                  textAlign: TextAlign.center,
                ),
              ),
              SizedBox(height: 16),
              Container(
                color: Colors.red[100],
                padding: EdgeInsets.all(16),
                child: Center(
                  child: IconButton(
                    icon: Icon(Icons.thumb_up, size: 40),
                    color: Colors.deepPurple,
                    onPressed: () {
                      print('IconButton Pressed');
                    },
                  ),
                ),
              ),
              SizedBox(height: 16),
              Container(
                color: Colors.orange[100],
                padding: EdgeInsets.all(16),
                child: Column(
                  children: [
                    TextField(
                      decoration: InputDecoration(
                        labelText: 'Name',
                        border: OutlineInputBorder(),
                      ),
                    ),
                    SizedBox(height: 10),
                    TextField(
                      decoration: InputDecoration(
                        labelText: 'Email',
                        border: OutlineInputBorder(),
                      ),
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
