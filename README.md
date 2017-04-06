class LottoController < ApplicationController
    def index
        @number=["1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "32", "33", "34", "35", "36", "37", "38", "39", "40", "41", "42", "43", "44", "45"]
        @number_1 = @number.sample + ".png"
         @number_2 = @number.sample + ".png"
          @number_3 = @number.sample + ".png"
           @number_4 = @number.sample + ".png"
            @number_5 = @number.sample + ".png"
             @number_6 = @number.sample + ".png"
              @number_bonus = @number.sample + ".png"
               @bonus = "bonus.png"
    end 
    
         
end
  
  
  
  
  <%=image_tag@number_1%><%=image_tag@number_2%><%=image_tag@number_3%><%=image_tag@number_4%><%=image_tag@number_5%><%=image_tag@number_6%> <%=image_tag@bonus%>  <%=image_tag@number_bonus%>