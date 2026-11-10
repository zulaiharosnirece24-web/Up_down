module up_down_counter (
    input clk,
    input reset,
    input up_down,
    output reg [3:0] count
);
always @(posedge clk or posedge reset) begin
    if (reset) begin
        count <= 4'b0000;
    end
    else begin
        if (up_down == 1'b0) begin
            count <= count + 1'b1;
        end
        else begin
            count <= count - 1'b1;
        end
    end
end
endmodule
