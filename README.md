# xiao
from abc import ABC, abstractmethod


class Coordinate(ABC):
    @abstractmethod
    def getC(self):
        pass


class Location(Coordinate):
    @abstractmethod
    def getC(self):
        print('x=0,y=0')


Coordinate = Location()
Coordinate.getC()
