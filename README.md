## Final View

![resim](https://github.com/muhammeddincmdx/Kt4-ComposeQuadrants/assets/54439858/12807895-b5fb-440c-8f15-eb8a3d48cfbd)


## 2X2 matrix
````
@Composable
fun ComposeQuadrants() {
    Column(modifier = Modifier.fillMaxSize()) {
        Row(Modifier.weight(1F)) {
            ComposeQuadrant(
                head = "Text composable",
                body = "Displays text and follows Material Design guidelines.",
                modifier = Modifier
                    .fillMaxHeight()
                    .weight(1f)
                    .background(color = Color(0xFFEADDFF))
                    .padding(16.dp)
            )
            ComposeQuadrant(
                head = "Image composable",
                body = "Creates a composable that lays out and draws a given Painter class object.",
                modifier = Modifier
                    .fillMaxHeight()
                    .weight(1f)
                    .background(color = Color(0xFFD0BCFF))//purple
                    .padding(16.dp)
            )
        }
        Row(Modifier.weight(1F)) {
            ComposeQuadrant(
                head = "Row composable",
                body = "A layout composable that places its children in a horizontal sequence.",
                modifier = Modifier
                    .fillMaxHeight()
                    .weight(1f)
                    .background(color = Color(0xFFB69DF8))//purple
                    .padding(16.dp)
            )
            ComposeQuadrant(
                head = "Column composable",
                body = "A layout composable that places its children in a vertical sequence.",
                modifier = Modifier
                    .fillMaxHeight()
                    .weight(1f)
                    .background(color = Color(0xFFF6EDFF))
                    .padding(16.dp)
            )
        }
    }
}
````
