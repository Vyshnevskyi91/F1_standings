# F1_standings
import pandas as pd

data = {
    "Pos": [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22],
    "Driver": ["Max Verstappen", "Sergio Perez", "Lewis Hamilton", "Fernando Alonso", "Charles Leclerc", "Lando Norris", "Carlos Sainz", "George Russell", "Oscar Piastri", "Lance Stroll", "Pierre Gasly", "Esteban Ocon", "Alexander Albon", "Yuki Tsunoda", "Valtteri Bottas", "Nico Hulkenberg", "Daniel Ricciardo", "Zhou Guanyu", "Kevin Magnussen", "Liam Lawson", "Logan Sargeant", "Nyck De Vries"],
    "Nationality": ["NED", "MEX", "GBR", "ESP", "MON", "GBR", "ESP", "GBR", "AUS", "CAN", "FRA", "FRA", "THA", "JPN", "FIN", "GER", "AUS", "CHN", "DEN", "NZL", "USA", "NED"],
    "Car": ["Red Bull Racing Honda RBPT", "Red Bull Racing Honda RBPT", "Mercedes", "Aston Martin Aramco Mercedes", "Ferrari", "McLaren Mercedes", "Ferrari", "Mercedes", "McLaren Mercedes", "Aston Martin Aramco Mercedes", "Alpine Renault", "Alpine Renault", "Williams Mercedes", "AlphaTauri Honda RBPT", "Alfa Romeo Ferrari", "Haas Ferrari", "AlphaTauri Honda RBPT", "Alfa Romeo Ferrari", "Haas Ferrari", "AlphaTauri Honda RBPT", "Williams Mercedes", "AlphaTauri Honda RBPT"],
    "PTS": [575, 285, 234, 206, 206, 205, 200, 175, 97, 74, 62, 58, 27, 17, 10, 9, 6, 6, 3, 2, 1, 0, 0]
}

df = pd.DataFrame(data)
print(df)
