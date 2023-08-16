import pytest
from app.calculator import Calculator

class TestCalc: # тестируем весь калькулятор нажатием на стрелку
    def setup(self):
        self.calc = Calculator

    def test_multiply_calculate_correctly(self): # умножение
        assert self.calc.multiply(self, 2, 3) == 6

    def test_division_calculate_correctly(self): # деление
        assert self.calc.division(self, 6, 3) == 2

    def test_subtraction_calculate_correctly(self): # вычитание
        assert self.calc.subtraction(self, 7, 2) == 5

    def test_adding_calculate_correctly(self): # сложение
        assert self.calc.adding(self, 2, 2) == 4

    def test_multiply_calculation_failed(self): # умножение
        assert self.calc.multiply(self, 3, 2) == 7 # негативный

    def test_division_calculation_failed(self): # деление
        assert self.calc.division(self, 8, 2) == 6 # негативный

    def test_subtraction_calculation_failed(self):  # вычитание
        assert self.calc.subtraction(self, 4, 2) == 3  # негативный

    def test_adding_calculation_failed(self): # сложение
        assert self.calc.adding(self, 2, 3) == 4 # негативный
