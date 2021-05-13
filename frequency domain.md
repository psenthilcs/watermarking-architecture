# watermarking-architecture
// Copyright (C) 1991-2009 Altera Corporation
// Your use of Altera Corporation's design tools, logic functions 
// and other software and tools, and its AMPP partner logic 
// functions, and any output files from any of the foregoing 
// (including device programming or simulation files), and any 
// associated documentation or information are expressly subject 
// to the terms and conditions of the Altera Program License 
// Subscription Agreement, Altera MegaCore Function License 
// Agreement, or other applicable license agreement, including, 
// without limitation, that your use is for the sole purpose of 
// programming logic devices manufactured by Altera and sold by 
// Altera or its authorized distributors.  Please refer to the 
// applicable agreement for further details.



module frqdomain(
	wen,
	clk,
	clk1,
	cle,
	A,
	B,
	radd,
	radd2,
	wadd,
	outp
);


input	wen;
input	clk;
input	clk1;
input	cle;
input	[7:0] A;
input	[7:0] B;
input	[9:0] radd;
input	[9:0] radd2;
input	[9:0] wadd;
output	[7:0] outp;

wire	[7:0] SYNTHESIZED_WIRE_0;
wire	[7:0] SYNTHESIZED_WIRE_1;
wire	[7:0] SYNTHESIZED_WIRE_2;
wire	[7:0] SYNTHESIZED_WIRE_3;
wire	[7:0] SYNTHESIZED_WIRE_4;
wire	[7:0] SYNTHESIZED_WIRE_5;
wire	[7:0] SYNTHESIZED_WIRE_6;
wire	[7:0] SYNTHESIZED_WIRE_7;
wire	[7:0] SYNTHESIZED_WIRE_8;
wire	[7:0] SYNTHESIZED_WIRE_9;
wire	[7:0] SYNTHESIZED_WIRE_10;
wire	[7:0] SYNTHESIZED_WIRE_11;
wire	[7:0] SYNTHESIZED_WIRE_12;
wire	[7:0] SYNTHESIZED_WIRE_13;
wire	[7:0] SYNTHESIZED_WIRE_14;
wire	[7:0] SYNTHESIZED_WIRE_15;
wire	[7:0] SYNTHESIZED_WIRE_16;
wire	[7:0] SYNTHESIZED_WIRE_17;
wire	[7:0] SYNTHESIZED_WIRE_18;
wire	[7:0] SYNTHESIZED_WIRE_19;
wire	[7:0] SYNTHESIZED_WIRE_20;
wire	[7:0] SYNTHESIZED_WIRE_21;
wire	[7:0] SYNTHESIZED_WIRE_22;
wire	[7:0] SYNTHESIZED_WIRE_23;
wire	[7:0] SYNTHESIZED_WIRE_24;
wire	[7:0] SYNTHESIZED_WIRE_25;
wire	[7:0] SYNTHESIZED_WIRE_26;
wire	[7:0] SYNTHESIZED_WIRE_27;
wire	[7:0] SYNTHESIZED_WIRE_28;
wire	[7:0] SYNTHESIZED_WIRE_29;
wire	[7:0] SYNTHESIZED_WIRE_30;
wire	[7:0] SYNTHESIZED_WIRE_31;
wire	[7:0] SYNTHESIZED_WIRE_32;
wire	[7:0] SYNTHESIZED_WIRE_33;
wire	[7:0] SYNTHESIZED_WIRE_34;
wire	[7:0] SYNTHESIZED_WIRE_35;
wire	[7:0] SYNTHESIZED_WIRE_36;
wire	[7:0] SYNTHESIZED_WIRE_37;
wire	[7:0] SYNTHESIZED_WIRE_38;
wire	[7:0] SYNTHESIZED_WIRE_39;
wire	[7:0] SYNTHESIZED_WIRE_40;
wire	[7:0] SYNTHESIZED_WIRE_41;
wire	[7:0] SYNTHESIZED_WIRE_42;
wire	[7:0] SYNTHESIZED_WIRE_43;
wire	[7:0] SYNTHESIZED_WIRE_44;
wire	[7:0] SYNTHESIZED_WIRE_45;
wire	[7:0] SYNTHESIZED_WIRE_46;
wire	[7:0] SYNTHESIZED_WIRE_47;
wire	[7:0] SYNTHESIZED_WIRE_48;
wire	[7:0] SYNTHESIZED_WIRE_49;
wire	[7:0] SYNTHESIZED_WIRE_50;
wire	[7:0] SYNTHESIZED_WIRE_51;
wire	[7:0] SYNTHESIZED_WIRE_52;
wire	[7:0] SYNTHESIZED_WIRE_53;
wire	[7:0] SYNTHESIZED_WIRE_54;
wire	[7:0] SYNTHESIZED_WIRE_55;
wire	[7:0] SYNTHESIZED_WIRE_56;
wire	[7:0] SYNTHESIZED_WIRE_57;
wire	[7:0] SYNTHESIZED_WIRE_58;
wire	[7:0] SYNTHESIZED_WIRE_59;
wire	[7:0] SYNTHESIZED_WIRE_60;
wire	[7:0] SYNTHESIZED_WIRE_61;
wire	[7:0] SYNTHESIZED_WIRE_62;
wire	[7:0] SYNTHESIZED_WIRE_63;
wire	[7:0] SYNTHESIZED_WIRE_64;
wire	[7:0] SYNTHESIZED_WIRE_65;
wire	[7:0] SYNTHESIZED_WIRE_66;
wire	[7:0] SYNTHESIZED_WIRE_67;
wire	[7:0] SYNTHESIZED_WIRE_68;
wire	[7:0] SYNTHESIZED_WIRE_69;
wire	[7:0] SYNTHESIZED_WIRE_70;
wire	[7:0] SYNTHESIZED_WIRE_71;
wire	[7:0] SYNTHESIZED_WIRE_72;
wire	[7:0] SYNTHESIZED_WIRE_73;
wire	[7:0] SYNTHESIZED_WIRE_74;
wire	[7:0] SYNTHESIZED_WIRE_75;
wire	[7:0] SYNTHESIZED_WIRE_76;
wire	[7:0] SYNTHESIZED_WIRE_77;
wire	[7:0] SYNTHESIZED_WIRE_78;
wire	[7:0] SYNTHESIZED_WIRE_79;
wire	[7:0] SYNTHESIZED_WIRE_80;
wire	[7:0] SYNTHESIZED_WIRE_81;
wire	[7:0] SYNTHESIZED_WIRE_82;
wire	[7:0] SYNTHESIZED_WIRE_83;
wire	[7:0] SYNTHESIZED_WIRE_84;
wire	[7:0] SYNTHESIZED_WIRE_85;





sertopar	b2v_inst(
	.clk(clk),
	.cle(cle),
	.inp(SYNTHESIZED_WIRE_0),
	.outp0(SYNTHESIZED_WIRE_20),
	.outp1(SYNTHESIZED_WIRE_21),
	.outp2(SYNTHESIZED_WIRE_22),
	.outp3(SYNTHESIZED_WIRE_23),
	.outp4(SYNTHESIZED_WIRE_24),
	.outp5(SYNTHESIZED_WIRE_25),
	.outp6(SYNTHESIZED_WIRE_26),
	.outp7(SYNTHESIZED_WIRE_27));


insertopar	b2v_inst1(
	.cle(cle),
	.clk(clk),
	.inp0(SYNTHESIZED_WIRE_1),
	.inp1(SYNTHESIZED_WIRE_2),
	.inp2(SYNTHESIZED_WIRE_3),
	.inp3(SYNTHESIZED_WIRE_4),
	.inp4(SYNTHESIZED_WIRE_5),
	.inp5(SYNTHESIZED_WIRE_6),
	.inp6(SYNTHESIZED_WIRE_7),
	.inp7(SYNTHESIZED_WIRE_8),
	.outp6(SYNTHESIZED_WIRE_66));


lpm_mult3	b2v_inst10(
	.dataa(SYNTHESIZED_WIRE_9),
	.result(SYNTHESIZED_WIRE_52));


lpm_mult3	b2v_inst11(
	.dataa(SYNTHESIZED_WIRE_10),
	.result(SYNTHESIZED_WIRE_54));


sertopar	b2v_inst12(
	.clk(clk),
	.cle(cle),
	.inp(SYNTHESIZED_WIRE_11),
	.outp0(SYNTHESIZED_WIRE_28),
	.outp1(SYNTHESIZED_WIRE_29),
	.outp2(SYNTHESIZED_WIRE_30),
	.outp3(SYNTHESIZED_WIRE_33),
	.outp4(SYNTHESIZED_WIRE_32),
	.outp5(SYNTHESIZED_WIRE_34),
	.outp6(SYNTHESIZED_WIRE_35),
	.outp7(SYNTHESIZED_WIRE_36));


lpm_mult1	b2v_inst13(
	.dataa(SYNTHESIZED_WIRE_12),
	.result(SYNTHESIZED_WIRE_37));


lpm_mult1	b2v_inst14(
	.dataa(SYNTHESIZED_WIRE_13),
	.result(SYNTHESIZED_WIRE_38));


lpm_mult1	b2v_inst15(
	.dataa(SYNTHESIZED_WIRE_14),
	.result(SYNTHESIZED_WIRE_39));


lpm_mult1	b2v_inst16(
	.dataa(SYNTHESIZED_WIRE_15),
	.result(SYNTHESIZED_WIRE_41));


lpm_mult1	b2v_inst17(
	.dataa(SYNTHESIZED_WIRE_16),
	.result(SYNTHESIZED_WIRE_40));


lpm_mult1	b2v_inst18(
	.dataa(SYNTHESIZED_WIRE_17),
	.result(SYNTHESIZED_WIRE_43));


lpm_mult1	b2v_inst19(
	.dataa(SYNTHESIZED_WIRE_18),
	.result(SYNTHESIZED_WIRE_44));


lpm_mult1	b2v_inst20(
	.dataa(SYNTHESIZED_WIRE_19),
	.result(SYNTHESIZED_WIRE_45));


lpm_dff4	b2v_inst29(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_20),
	.q(SYNTHESIZED_WIRE_31));


lpm_ram_dp1	b2v_inst3(
	.wren(wen),
	.clock(clk),
	.data(B),
	.rdaddress(radd),
	.wraddress(wadd),
	.q(SYNTHESIZED_WIRE_65));


lpm_dff4	b2v_inst30(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_21),
	.q(SYNTHESIZED_WIRE_42));


lpm_dff4	b2v_inst31(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_22),
	.q(SYNTHESIZED_WIRE_53));


lpm_dff4	b2v_inst32(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_23),
	.q(SYNTHESIZED_WIRE_64));


lpm_dff4	b2v_inst33(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_24),
	.q(SYNTHESIZED_WIRE_82));


lpm_dff4	b2v_inst34(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_25),
	.q(SYNTHESIZED_WIRE_85));


lpm_dff4	b2v_inst35(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_26),
	.q(SYNTHESIZED_WIRE_9));


lpm_dff4	b2v_inst36(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_27),
	.q(SYNTHESIZED_WIRE_10));


lpm_dff4	b2v_inst37(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_28),
	.q(SYNTHESIZED_WIRE_12));


lpm_dff4	b2v_inst38(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_29),
	.q(SYNTHESIZED_WIRE_13));


lpm_dff4	b2v_inst39(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_30),
	.q(SYNTHESIZED_WIRE_14));


lpm_mult3	b2v_inst4(
	.dataa(SYNTHESIZED_WIRE_31),
	.result(SYNTHESIZED_WIRE_46));


lpm_dff4	b2v_inst40(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_32),
	.q(SYNTHESIZED_WIRE_16));


lpm_dff4	b2v_inst41(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_33),
	.q(SYNTHESIZED_WIRE_15));


lpm_dff4	b2v_inst42(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_34),
	.q(SYNTHESIZED_WIRE_17));


lpm_dff4	b2v_inst43(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_35),
	.q(SYNTHESIZED_WIRE_18));


lpm_dff4	b2v_inst44(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_36),
	.q(SYNTHESIZED_WIRE_19));


lpm_dff4	b2v_inst45(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_37),
	.q(SYNTHESIZED_WIRE_69));


lpm_dff4	b2v_inst46(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_38),
	.q(SYNTHESIZED_WIRE_71));


lpm_dff4	b2v_inst47(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_39),
	.q(SYNTHESIZED_WIRE_73));


lpm_dff4	b2v_inst48(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_40),
	.q(SYNTHESIZED_WIRE_77));


lpm_dff4	b2v_inst49(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_41),
	.q(SYNTHESIZED_WIRE_75));


lpm_mult3	b2v_inst5(
	.dataa(SYNTHESIZED_WIRE_42),
	.result(SYNTHESIZED_WIRE_47));


lpm_dff4	b2v_inst50(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_43),
	.q(SYNTHESIZED_WIRE_79));


lpm_dff4	b2v_inst51(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_44),
	.q(SYNTHESIZED_WIRE_81));


lpm_dff4	b2v_inst52(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_45),
	.q(SYNTHESIZED_WIRE_84));


lpm_dff4	b2v_inst53(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_46),
	.q(SYNTHESIZED_WIRE_68));


lpm_dff4	b2v_inst54(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_47),
	.q(SYNTHESIZED_WIRE_70));


lpm_dff4	b2v_inst55(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_48),
	.q(SYNTHESIZED_WIRE_72));


lpm_dff4	b2v_inst56(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_49),
	.q(SYNTHESIZED_WIRE_74));


lpm_dff4	b2v_inst57(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_50),
	.q(SYNTHESIZED_WIRE_76));


lpm_dff4	b2v_inst58(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_51),
	.q(SYNTHESIZED_WIRE_78));


lpm_dff4	b2v_inst59(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_52),
	.q(SYNTHESIZED_WIRE_80));


lpm_mult3	b2v_inst6(
	.dataa(SYNTHESIZED_WIRE_53),
	.result(SYNTHESIZED_WIRE_48));


lpm_dff4	b2v_inst60(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_54),
	.q(SYNTHESIZED_WIRE_83));


lpm_dff4	b2v_inst61(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_55),
	.q(SYNTHESIZED_WIRE_1));


lpm_dff4	b2v_inst62(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_56),
	.q(SYNTHESIZED_WIRE_2));


lpm_dff4	b2v_inst63(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_57),
	.q(SYNTHESIZED_WIRE_3));


lpm_dff4	b2v_inst64(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_58),
	.q(SYNTHESIZED_WIRE_4));


lpm_dff4	b2v_inst65(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_59),
	.q(SYNTHESIZED_WIRE_5));


lpm_dff4	b2v_inst66(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_60),
	.q(SYNTHESIZED_WIRE_6));


lpm_dff4	b2v_inst67(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_61),
	.q(SYNTHESIZED_WIRE_7));


lpm_dff4	b2v_inst68(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_62),
	.q(SYNTHESIZED_WIRE_8));


lpm_dff4	b2v_inst69(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_63),
	.q(SYNTHESIZED_WIRE_0));


lpm_mult3	b2v_inst7(
	.dataa(SYNTHESIZED_WIRE_64),
	.result(SYNTHESIZED_WIRE_49));


lpm_dff4	b2v_inst70(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_65),
	.q(SYNTHESIZED_WIRE_11));


lpm_dff4	b2v_inst71(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_66),
	.q(SYNTHESIZED_WIRE_67));


lpm_ram_dp2	b2v_inst72(
	
	.wren_b(wen),
	.clock_a(clk1),
	.clock_b(clk),
	.address_a(radd2),
	.address_b(radd),
	.data_a(SYNTHESIZED_WIRE_67),
	.data_b(A),
	.q_a(outp),
	.q_b(SYNTHESIZED_WIRE_63));


lpm_add_sub6	b2v_inst73(
	.dataa(SYNTHESIZED_WIRE_68),
	.datab(SYNTHESIZED_WIRE_69),
	.result(SYNTHESIZED_WIRE_55));


lpm_add_sub6	b2v_inst74(
	.dataa(SYNTHESIZED_WIRE_70),
	.datab(SYNTHESIZED_WIRE_71),
	.result(SYNTHESIZED_WIRE_56));


lpm_add_sub6	b2v_inst75(
	.dataa(SYNTHESIZED_WIRE_72),
	.datab(SYNTHESIZED_WIRE_73),
	.result(SYNTHESIZED_WIRE_57));


lpm_add_sub6	b2v_inst76(
	.dataa(SYNTHESIZED_WIRE_74),
	.datab(SYNTHESIZED_WIRE_75),
	.result(SYNTHESIZED_WIRE_58));


lpm_add_sub6	b2v_inst77(
	.dataa(SYNTHESIZED_WIRE_76),
	.datab(SYNTHESIZED_WIRE_77),
	.result(SYNTHESIZED_WIRE_59));


lpm_add_sub6	b2v_inst78(
	.dataa(SYNTHESIZED_WIRE_78),
	.datab(SYNTHESIZED_WIRE_79),
	.result(SYNTHESIZED_WIRE_60));


lpm_add_sub6	b2v_inst79(
	.dataa(SYNTHESIZED_WIRE_80),
	.datab(SYNTHESIZED_WIRE_81),
	.result(SYNTHESIZED_WIRE_61));


lpm_mult3	b2v_inst8(
	.dataa(SYNTHESIZED_WIRE_82),
	.result(SYNTHESIZED_WIRE_50));


lpm_add_sub6	b2v_inst80(
	.dataa(SYNTHESIZED_WIRE_83),
	.datab(SYNTHESIZED_WIRE_84),
	.result(SYNTHESIZED_WIRE_62));


lpm_mult3	b2v_inst9(
	.dataa(SYNTHESIZED_WIRE_85),
	.result(SYNTHESIZED_WIRE_51));


endmodule
