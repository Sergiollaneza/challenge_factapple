#' Print pineapple facts
#'
#' Prints on the console a pineapple fact from a list of 16. The selected fact can be chosen or can be random.
#' @param number Fact number to be printed from 1 to 16. Defaults to be random.
#' @importFrom readr read_csv
#' @export
#' @example generateFact()

generateFact <- function(number = sample(1:16, 1)){

  if(number > 16 | number < 1){
    stop("Please, choose a number between 1 and 16")
  }

  data(facts)
  print(facts[number,])

}
