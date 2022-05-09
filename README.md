# Flutter
import 'dart:html';

import 'package:flutter/material.dart';

class ResultPage extends StatelessWidget {
  const ResultPage({
    Key? key,
    required this.interpretation,
    required this.interpretation,
    required this.interpretation,
}) : super(key: key);

@override
Widget build(BuildContext context) {
  return Scaffold(
    appBar: AppBar(title: Text('BMI CALCULATOR')),
    body: Column(
      mainAxisAlignment: MainAxisAlignment.spaceEvenly,
      crossAxisAlignment: CrossAxisAlignment.stretch,
      children: [
        Expanded(
          child: Container(
            padding: EdgeInsets.all(15),
            alignment: Alignment.bottomLeft,
          
          )
        )
      ],
    ),
  );
}
} 
