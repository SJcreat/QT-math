#include "mainwindow.h"
#include "ui_mainwindow.h"
#include <QDebug>
MainWindow::MainWindow(QWidget *parent)
    : QMainWindow(parent)
    , ui(new Ui::MainWindow)
{
    ui->setupUi(this);


    int x=50;

    qDebug()<<x+2<<"\n"<<x-2<<"\n"<<x*2<<"\n"<<x/2; // 사칙연산

    qDebug()<<x%7;    // 나머지

    qDebug()<<(int)x/7; // 몫

    qDebug()<<sqrt(x); // 루트 x

    qDebug()<<pow(x,2); // x의 제곱

    qDebug()<<round(x/7); // 반올림
}

MainWindow::~MainWindow()
{
    delete ui;
}

