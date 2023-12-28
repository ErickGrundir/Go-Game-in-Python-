# Go-Game-in-Python-
Go Game in Python:
class GoGame:
    def __init__(self):
        self.board_size = 19
        self.board = [['.' for _ in range(self.board_size)] for _ in range(self.board_size)]

    def display_board(self):
        for row in self.board:
            print(' '.join(row))

# Example usage
go_game = GoGame()
go_game.display_board()
