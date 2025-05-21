class MurderStatsManager:
    def __init__(self):
        self.data = {}

    def add_data(self, continent, country, city, count):
        key = f"{continent}: {country} - {city}"
        self.data[key] = count

    def get_stats(self):
        for location, count in self.data.items():
            print(f"{location}: {count} murders")

data = MurderStatsManager()
data.add_data("Europe", "Estonia", "Tallinn", 5)
data.add_data("Europe", "Finland", "Helsinki", 3)
data.add_data("Asia", "Japan", "Tokyo", 8)

data.get_stats()
