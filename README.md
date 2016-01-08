# swift
struct Ma {

let rows: Int, columns: Int
var grid: [Double]


init(rows: Int, columns: Int) {
self.rows = rows
self.columns = columns
grid = Array(count: rows * columns, repeatedValue: 0.0)}

subscript(row: Int, column: Int) -> Double {
get {

return grid[(row * columns) + column]
}
set {

grid[(row * columns) + column] = newValue
}
}
}

var matrix = Ma(rows: 2, columns: 2)
print(matrix.grid)//[0.0, 0.0, 0.0, 0.0]

matrix[0, 1] = 1.5
matrix[1, 0] = 3.2

print(matrix.grid)//[0.0, 1.5, 3.2, 0.0]

111111111111111111111111111111111111111111111
222222222222222222222222222222222222222222222

在商场新建个分支lenovo 加了这句！