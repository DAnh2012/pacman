# pacman
link youtube: https://youtu.be/Eot7-R5ufZU
Mô tả: thuật toán tìm đường dùng trong game pacman

search.py bao gồm DFS, BFS, uniform cost và A* 
searchAgent.py bao gồm các hành động dùng để điều khiển pacman

search.py được khởi tạo thêm class Node đại diện cho pacman
Method expand trả lại mảng các vị trí hợp lệ tiếp theo
Method child_node gán 1 node với mỗi vị trí hợp lệ tiếp theo
Method path trả lại 1 list các vị trí đã đi qua từ root đến mục tiêu
Method solution trả lại mảng các action thực hiện
