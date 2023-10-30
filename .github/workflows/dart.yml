import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(
        colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
        useMaterial3: true,
      ),
      home: const MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

class MyHomePage extends StatefulWidget {
  const MyHomePage({super.key, required this.title});


  final String title;

  @override
  State<MyHomePage> createState() => _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {
  int _counter = 0;

  double redc = 0;
  double greenc = 0;
  double bluec = 0;



  @override
  Widget build(BuildContext context) {
    return Scaffold(
        backgroundColor: Color.fromARGB(255, redc.round(), greenc.round(), bluec.round()),
      body: Center(
        child: Column(
          children: [
            Slider(value: redc, max: 255, onChanged: (double redr){setState(() {
              redc = redr;

            });}),
            Slider(value: greenc, max: 255, onChanged: (double greenr){setState(() {
              greenc = greenr;
              print(greenr);
            });}),
            Slider(value: bluec, max: 255, onChanged: (double bluer){setState(() {
              bluec = bluer;
            });})
          ],
            ),
      )
        );
  }
}
