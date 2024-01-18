from PyQt5 import QtCore, QtGui, QtWidgets


class Ui_MainWindow(object):
    def setupUi(self, MainWindow):
        MainWindow.setObjectName("MainWindow")
        MainWindow.resize(372, 451)
        font = QtGui.QFont()
        font.setPointSize(17)
        font.setBold(True)
        font.setWeight(75)
        MainWindow.setFont(font)
        self.centralwidget = QtWidgets.QWidget(MainWindow)
        self.centralwidget.setObjectName("centralwidget")
        self.label_result = QtWidgets.QLabel(self.centralwidget)
        self.label_result.setGeometry(QtCore.QRect(0, 0, 371, 50))
        font = QtGui.QFont()
        font.setPointSize(17)
        font.setBold(True)
        font.setWeight(75)
        self.label_result.setFont(font)
        self.label_result.setStyleSheet("background-color: rgb(255, 170, 255);\n"
                                        "color: rgb(255, 0, 0);")
        self.label_result.setObjectName("label_result")
        self.btn_zero = QtWidgets.QPushButton(self.centralwidget)
        self.btn_zero.setGeometry(QtCore.QRect(0, 350, 101, 101))
        self.btn_zero.setStyleSheet("background-color: rgb(255, 170, 255);")
        self.btn_zero.setObjectName("btn_zero")
        self.btn_equally = QtWidgets.QPushButton(self.centralwidget)
        self.btn_equally.setGeometry(QtCore.QRect(100, 350, 131, 101))
        font = QtGui.QFont()
        font.setPointSize(17)
        font.setBold(True)
        font.setWeight(75)
        self.btn_equally.setFont(font)
        self.btn_equally.setStyleSheet("background-color: rgb(255, 85, 0);")
        self.btn_equally.setObjectName("btn_equally")
        self.btn_2 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_2.setGeometry(QtCore.QRect(100, 250, 100, 100))
        font = QtGui.QFont()
        font.setPointSize(17)
        self.btn_2.setFont(font)
        self.btn_2.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_2.setObjectName("btn_2")
        self.btn_5 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_5.setGeometry(QtCore.QRect(100, 150, 100, 100))
        self.btn_5.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_5.setObjectName("btn_5")
        self.btn_8 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_8.setGeometry(QtCore.QRect(100, 50, 101, 101))
        self.btn_8.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_8.setObjectName("btn_8")
        self.btn_1 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_1.setGeometry(QtCore.QRect(0, 250, 100, 100))
        self.btn_1.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_1.setObjectName("btn_1")
        self.btn_7 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_7.setGeometry(QtCore.QRect(0, 50, 101, 101))
        font = QtGui.QFont()
        font.setPointSize(17)
        font.setBold(True)
        font.setWeight(75)
        self.btn_7.setFont(font)
        self.btn_7.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_7.setObjectName("btn_7")
        self.btn_4 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_4.setGeometry(QtCore.QRect(0, 150, 100, 100))
        self.btn_4.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_4.setObjectName("btn_4")
        self.btn_3 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_3.setGeometry(QtCore.QRect(200, 250, 100, 100))
        font = QtGui.QFont()
        font.setPointSize(17)
        self.btn_3.setFont(font)
        self.btn_3.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_3.setObjectName("btn_3")
        self.btn_9 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_9.setGeometry(QtCore.QRect(200, 50, 101, 101))
        self.btn_9.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_9.setObjectName("btn_9")
        self.btn_6 = QtWidgets.QPushButton(self.centralwidget)
        self.btn_6.setGeometry(QtCore.QRect(200, 150, 100, 100))
        self.btn_6.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_6.setObjectName("btn_6")

        self.btn_plus = QtWidgets.QPushButton(self.centralwidget)
        self.btn_plus.setGeometry(QtCore.QRect(300, 50, 71, 101))
        self.btn_plus.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_plus.setObjectName("btn_plus")
        self.btn_minus = QtWidgets.QPushButton(self.centralwidget)
        self.btn_minus.setGeometry(QtCore.QRect(300, 150, 71, 100))
        self.btn_minus.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_minus.setObjectName("btn_minus")
        self.btn_multiplication = QtWidgets.QPushButton(self.centralwidget)
        self.btn_multiplication.setGeometry(QtCore.QRect(300, 250, 71, 100))
        font = QtGui.QFont()
        font.setPointSize(17)
        self.btn_multiplication.setFont(font)
        self.btn_multiplication.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_multiplication.setObjectName("btn_multiplication")
        self.btn_div = QtWidgets.QPushButton(self.centralwidget)
        self.btn_div.setGeometry(QtCore.QRect(300, 350, 71, 101))
        font = QtGui.QFont()
        font.setPointSize(17)
        self.btn_div.setFont(font)
        self.btn_div.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_div.setObjectName("btn_div")
        self.btn_point = QtWidgets.QPushButton(self.centralwidget)
        self.btn_point.setGeometry(QtCore.QRect(230, 350, 71, 100))
        font = QtGui.QFont()
        font.setPointSize(17)
        self.btn_point.setFont(font)
        self.btn_point.setStyleSheet("background-color: rgb(255, 170, 0);")
        self.btn_point.setObjectName("btn_point")
        MainWindow.setCentralWidget(self.centralwidget)

        self.retranslateUi(MainWindow)
        QtCore.QMetaObject.connectSlotsByName(MainWindow)

        self.add_functions()

        self.is_equal = False

    def retranslateUi(self, MainWindow):
        _translate = QtCore.QCoreApplication.translate
        MainWindow.setWindowTitle(_translate("MainWindow", "Calculator"))
        self.label_result.setText(_translate("MainWindow", "0"))
        self.btn_zero.setText(_translate("MainWindow", "0"))
        self.btn_equally.setText(_translate("MainWindow", "="))
        self.btn_2.setText(_translate("MainWindow", "2"))
        self.btn_5.setText(_translate("MainWindow", "5"))
        self.btn_8.setText(_translate("MainWindow", "8"))
        self.btn_1.setText(_translate("MainWindow", "1"))
        self.btn_7.setText(_translate("MainWindow", "7"))
        self.btn_4.setText(_translate("MainWindow", "4"))
        self.btn_3.setText(_translate("MainWindow", "3"))
        self.btn_9.setText(_translate("MainWindow", "9"))
        self.btn_6.setText(_translate("MainWindow", "6"))
        self.btn_plus.setText(_translate("MainWindow", "+"))
        self.btn_minus.setText(_translate("MainWindow", "-"))
        self.btn_multiplication.setText(_translate("MainWindow", "*"))
        self.btn_div.setText(_translate("MainWindow", "/"))
        self.btn_point.setText(_translate("MainWindow", "."))

    def add_functions(self):
        self.btn_zero.clicked.connect(lambda: self.write_number(self.btn_zero.text()))
        self.btn_1.clicked.connect(lambda: self.write_number(self.btn_1.text()))
        self.btn_2.clicked.connect(lambda: self.write_number(self.btn_2.text()))
        self.btn_3.clicked.connect(lambda: self.write_number(self.btn_3.text()))
        self.btn_4.clicked.connect(lambda: self.write_number(self.btn_4.text()))
        self.btn_5.clicked.connect(lambda: self.write_number(self.btn_5.text()))
        self.btn_6.clicked.connect(lambda: self.write_number(self.btn_6.text()))
        self.btn_7.clicked.connect(lambda: self.write_number(self.btn_7.text()))
        self.btn_8.clicked.connect(lambda: self.write_number(self.btn_8.text()))
        self.btn_9.clicked.connect(lambda: self.write_number(self.btn_9.text()))
        self.btn_plus.clicked.connect(lambda: self.write_number(self.btn_plus.text()))
        self.btn_minus.clicked.connect(lambda: self.write_number(self.btn_minus.text()))
        self.btn_equally.clicked.connect(lambda: self.write_number(self.btn_equally.text()))
        self.btn_multiplication.clicked.connect(lambda: self.write_number(self.btn_multiplication.text()))
        self.btn_div.clicked.connect(lambda: self.write_number(self.btn_div.text()))
        self.btn_point.clicked.connect(lambda: self.write_number(self.btn_point.text()))

        self.btn_equally.clicked.connect(self.results)

    def write_number(self, number):
        if self.label_result.text() == "0" or self.is_equal:
            self.label_result.setText(number)
            self.is_equal = False
        else:
            self.label_result.setText(self.label_result.text() + number)

    def results(self):
        if not self.is_equal:
            s = self.label_result.text()
            res = eval(s[:len(s) - 1])
            self.label_result.setText("Результат: " + str(res))
            self.is_equal = True


if __name__ == "__main__":
    import sys

    app = QtWidgets.QApplication(sys.argv)
    MainWindow = QtWidgets.QMainWindow()
    ui = Ui_MainWindow()
    ui.setupUi(MainWindow)
    MainWindow.show()
    sys.exit(app.exec_())
