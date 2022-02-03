# Expensei
Money Management Application

TODO:

 * homeScreen:
    - input:
        - popout "+" button to add an expense/deposit/income/bills
        - incomes will add money periodically [workIncome]
        - deposits will add money for specific occations [soldSomething]
        - bills will reduce money periodically [water]
        - expenses will reduce money for specific occations [eatingOut]
    - overview:
        - Weekly Report:
            - shows this week's upcoming bills and incomes
        - can push notifications of bills and incomes {Will be completed later as push notifs are annoying}
 * cashFlowAgenda
        - string [angendaSort]
        - shows the most recent expenses and deposits
        - seperate, incomes and bills
        - automatically sort seperate lists in the following manner:
            - upcoming: early to late
            - past: recent to oldest
 * cashFlowCalendar
        - string [toggleDisplay]
            - determines what time frame is displayed
                - [2week]
                - [thisMonth]
                - certainMonth
        - bool [toggleType]
        - when toggled for expenses, show
 * processes
    - yearlyExpenseDoc:
        - app over time compiles a list of all expenses and incomes for 1 year in a single document viewable by the user upon request.
    - incomes:
        - [workIncome]
        - [landlordMoney]
    - bills:
        - [water]
        - [electric]
        - [utilities]
        - [internet]
        - [dataPlan]
        - [mortageRent]
        - [insurance]
        - [taxes]
        - [subscriptions]
    - expenses:
        - [groceries]
        - [parkingTickets]
    - deposits:
        - [lottery]
        - [soldSomething]
