# Given a List of words, return the words that can be typed using letters of alphabet on 
# only one row's of American keyboard like the image below. 
# Input: ["Hello", "Alaska", "Dad", "Peace"]
# Output: ["Alaska", "Dad"]
*******Solution*******
class Solution:
    def numRookCaptures(self, board: List[List[str]]) -> int:
        for i in range(len(board)):
            try:
                Rook_y, Rook_x = (i, board[i].index('R'))
            except:
                ValueError

        print('rook co - ordintaes are', Rook_x, Rook_y)
        count = 0
        for i in range(Rook_x, 8):
            if board[Rook_y][i] == 'B':
                # print('bishop found')
                break
            elif board[Rook_y][i] == 'p':
                count = count + 1
                break

        for i in range(Rook_x, 0, -1):
            if board[Rook_y][i] == 'B':
                # print('bishop found')
                break
            elif board[Rook_y][i] == 'p':
                count = count + 1
                break

        for i in range(Rook_x, 8):
            if board[i][Rook_x] == 'B':
                # print('bishop found')
                break
            elif board[i][Rook_x] == 'p':
                count = count + 1
                break

        for i in range(Rook_x, 0, -1):
            if board[i][Rook_x] == 'B':
                # print('bishop found')
                break
            elif board[i][Rook_x] == 'p':
                count = count + 1
                break


        return(count)
