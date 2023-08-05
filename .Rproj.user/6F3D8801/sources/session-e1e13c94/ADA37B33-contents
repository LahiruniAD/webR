# Load required libraries
library(shiny)
library(shinydashboard)
library(shinydashboardPlus)
library(webshot)
library(webshot2)

# Define UI
ui <- dashboardPage(
  dashboardHeader(title = "DSC 3091"),
  dashboardSidebar(
    sidebarMenu(
      menuItem("Dashboard", tabName = "dashboard", icon = icon("dashboard")),
      menuItem("Home", tabName = "Home"),
      menuItem("Lecture Notes", icon = icon("bar-chart-o"),
               menuSubItem("Lecture 01", tabName = "subitem1"),
               menuSubItem("Lecture 02", tabName = "subitem2"),
               menuSubItem("Lecture 03", tabName = "subitem3"),
               menuSubItem("Lecture 04", tabName = "subitem4"),
               menuSubItem("Lecture 05", tabName = "subitem5"),
               menuSubItem("Lecture 06", tabName = "subitem6"),
               menuSubItem("Lecture 07", tabName = "subitem7"),
               menuSubItem("Lecture 08", tabName = "subitem8"),
               menuSubItem("Lecture 09", tabName = "subitem9"),
               menuSubItem("Lecture 10", tabName = "subitem10"),
               menuSubItem("Lecture 11", tabName = "subitem11")
      )
    )
  ),
  dashboardBody(
    tags$style(HTML("
      .h1-center, .h2-center, .image-container {
        text-align: center;
      }
      .justify-text {
        text-align: center;
      }
      .larger-font {
        font-size: 17px;
      }
      /* Force full-screen display of the PDF */
      .pdf-container {
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: #f4f4f4; /* Set the gray background color */
        margin-bottom: 0; /* Remove bottom margin */
      }
      .pdf-object {
        width: 100%;
        height: 95vh; /* Adjust the height here to leave some space at the bottom */
        margin-top: 50px; /* Add top margin */
      }
    ")),
    tabItems(
      tabItem(
        tags$style(".h1-center { text-align: center; }"),
        tabName = "Home",
        h1(class = "h1-center", HTML("<b>DSC 3091 - Advanced Statistical Applications 1</b>")),
        h3(class = "h2-center", HTML("<b>Introduction</b>")),
        div(class = "image-container", img(src = "pic_home.jpg", width = "450px", height = "350px")),
        p(class = c("justify-text", "larger-font"), "Many statistics-related challenges arise from a lack of solid theoretical grounding among practitioners and applied statisticians. Additionally, their limited familiarity with the latest technologies and tools can hinder their ability to provide optimal solutions to problems efficiently. The Advanced Statistics Applications I course addresses these issues by empowering students to apply statistical theory in solving real-life problems using various statistical tools and software packages. Through hands-on laboratory sessions, students can augment their technical expertise and gain valuable practical experience.
          The course curriculum encompasses essential theoretical concepts such as Point and interval estimation, Hypothesis testing, Statistical quality control, Categorical data analysis, and multiple linear regression. These fundamental principles serve as building blocks for tackling complex statistical challenges in diverse fields.
          In addition to theoretical components, the course also includes practical sessions where students learn to utilize cutting-edge R packages for manipulating complex data and creating academic documents. This exposure to modern statistical software enhances students' analytical abilities and equips them with valuable skills that are in high demand in today's data-driven world.
          By bridging the gap between theoretical knowledge and practical application, the Advanced Statistics Applications I course equips aspiring statisticians with the necessary tools to become proficient problem solvers, contributing to advancements in various industries and research domains.")
      ),
      tabItem(
        tabName = "subitem1",
        h2("Lecture 01"),
        # Display the PDF for Lecture 01 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_01.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem2",
        h2("Lecture 02"),
        # Display the PDF for Lecture 02 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_02.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem3",
        h2("Lecture 03"),
        # Display the PDF for Lecture 03 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_03.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem4",
        h2("Lecture 04"),
        # Display the PDF for Lecture 04 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_04.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem5",
        h2("Lecture 05"),
        # Display the PDF for Lecture 05 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_05.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem6",
        h2("Lecture 06"),
        # Display the PDF for Lecture 06 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_06.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem7",
        h2("Lecture 07"),
        # Display the PDF for Lecture 07 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_07.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem8",
        h2("Lecture 08"),
        # Display the PDF for Lecture 08 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_08.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem9",
        h2("Lecture 09"),
        # Display the PDF for Lecture 10 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_09.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem10",
        h2("Lecture 10"),
        # Display the PDF for Lecture 10 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_10.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem(
        tabName = "subitem11",
        h2("Lecture 11"),
        # Display the PDF for Lecture 05 with minimize and maximize icons
        div(class = "pdf-container",
            tags$embed(
              class = "pdf-object",
              src = "Lectures/Lecture_11.pdf",
              type = "application/pdf"
            )
        )
      ),
      tabItem("dashboard",
              div(class = "image-container", img(src = "pic_dash1.jpg", width = "1250px", height = "660px"))
      )
    )
  )
)

# Create Shiny app
shinyApp(ui, server = function(input, output) { })
