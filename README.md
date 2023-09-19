import 'dart:ui';

import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.lightBlue,
        appBar: AppBar(
          backgroundColor: Colors.lightBlue[400],
          title: Text(
            "Weather App",
            style: TextStyle(color: Colors.white),
          ),
        ),
        body: Center(
          child: Column(
            children: [
              SizedBox(
                height: 40,
              ),
              Text(
                "Welkom",
                style: TextStyle(
                  color: Colors.white,
                  fontSize: 32,
                  fontWeight: FontWeight.w400,
                ),
              ),
              SizedBox(
                height: 10,
              ),
              Text(
                "29°C",
                style: TextStyle(
                  color: Colors.white,
                  fontSize: 64,
                  fontWeight: FontWeight.w300,
                ),
              ),
              SizedBox(
                height: 10,
              ),
              const Text(
                "30/6°C",
                style: TextStyle(
                  color: Colors.white,
                  fontSize: 20,
                ),
              ),
              const SizedBox(
                height: 7,
              ),
              const Text(
                "Clear",
                style: TextStyle(
                  color: Colors.white,
                  fontSize: 20,
                ),
              ),
              SizedBox(
                height: 30,
              ),
              Padding(
                padding: const EdgeInsets.only(
                  left: 20,
                  right: 20,
                ),
                child: Container(
                  height: 150,
                  decoration: const BoxDecoration(
                    color: Color.fromARGB(48, 179, 232, 233),
                    borderRadius: BorderRadius.all(
                      Radius.circular(
                        15,
                      ),
                    ),
                  ),
                  child: ListView(
                    scrollDirection: Axis.horizontal,
                    children: [
                      Column(
                        children: [
                          Padding(
                            padding: const EdgeInsets.only(
                              left: 20,
                              top: 20,
                              right: 20,
                            ),
                            child: Row(
                              children: [
                                Text(
                                  "3:00 PM",
                                  style: TextStyle(color: Colors.white),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "4:00 PM",
                                  style: TextStyle(color: Colors.white),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "5:00 PM",
                                  style: TextStyle(color: Colors.white),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "6:00 PM",
                                  style: TextStyle(color: Colors.white),
                                ),
                              ],
                            ),
                          ),
                          Padding(
                            padding: const EdgeInsets.only(
                              left: 5,
                              top: 20,
                            ),
                            child: Row(
                              children: [
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                                SizedBox(width: 55),
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                                SizedBox(width: 55),
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                                SizedBox(width: 55),
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                              ],
                            ),
                          ),
                          Padding(
                            padding: const EdgeInsets.only(
                              left: 20,
                              top: 20,
                              right: 20,
                            ),
                            child: Row(
                              children: [
                                Text(
                                  "29°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "29°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                                SizedBox(width: 25),
                                Text(
                                  "30°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "30°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      )
                    ],
                  ),
                ),
              ),
              SizedBox(height: 30),
              Padding(
                padding: const EdgeInsets.only(
                  left: 20,
                  right: 20,
                ),
                child: Container(
                  height: 150,
                  decoration: BoxDecoration(
                    color: Color.fromARGB(48, 179, 232, 233),
                    borderRadius: BorderRadius.all(
                      Radius.circular(
                        15,
                      ),
                    ),
                  ),
                  child: ListView(
                    scrollDirection: Axis.horizontal,
                    children: [
                      Column(
                        children: [
                          Padding(
                            padding: const EdgeInsets.only(
                              left: 20,
                              top: 20,
                              right: 20,
                            ),
                            child: Row(
                              children: [
                                Text(
                                  "Today",
                                  style: TextStyle(color: Colors.white),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "Tommorrow",
                                  style: TextStyle(color: Colors.white),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "Wednesday",
                                  style: TextStyle(color: Colors.white),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "Thursday",
                                  style: TextStyle(color: Colors.white),
                                ),
                              ],
                            ),
                          ),
                          Padding(
                            padding: const EdgeInsets.only(
                              left: 5,
                              top: 20,
                            ),
                            child: Row(
                              children: [
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                                SizedBox(width: 55),
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                                SizedBox(width: 55),
                                Icon(
                                  Icons.wb_sunny,
                                  color: Colors.yellow[600],
                                ),
                                SizedBox(width: 55),
                                Icon(
                                  Icons.cloud,
                                  color: Colors.white,
                                ),
                              ],
                            ),
                          ),
                          Padding(
                            padding: const EdgeInsets.only(
                              left: 20,
                              top: 20,
                              right: 20,
                            ),
                            child: Row(
                              children: [
                                Text(
                                  "29°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "29°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                                SizedBox(width: 25),
                                Text(
                                  "30°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                                SizedBox(width: 30),
                                Text(
                                  "30°C",
                                  style: TextStyle(
                                    color: Colors.white,
                                    fontSize: 25,
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      )
                    ],
                  ),
                ),
              )
            ],
          ),
        ),
      ),
    ),
  );
}
