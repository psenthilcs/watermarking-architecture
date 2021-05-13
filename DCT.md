

module sertopar(
	clk,
	cle,
	inp,
	outp0,
	outp1,
	outp2,
	outp3,
	outp4,
	outp5,
	outp6,
	outp7,
	q0
);


input	clk;
input	cle;
input	[7:0] inp;
output	[7:0] outp0;
output	[7:0] outp1;
output	[7:0] outp2;
output	[7:0] outp3;
output	[7:0] outp4;
output	[7:0] outp5;
output	[7:0] outp6;
output	[7:0] outp7;
output	[2:0] q0;

wire	[2:0] q_ALTERA_SYNTHESIZED0;
wire	[7:0] SYNTHESIZED_WIRE_161;
wire	[7:0] SYNTHESIZED_WIRE_162;
wire	[7:0] SYNTHESIZED_WIRE_163;
wire	[7:0] SYNTHESIZED_WIRE_164;
wire	[7:0] SYNTHESIZED_WIRE_4;
wire	[7:0] SYNTHESIZED_WIRE_5;
wire	[7:0] SYNTHESIZED_WIRE_6;
wire	[7:0] SYNTHESIZED_WIRE_7;
wire	[7:0] SYNTHESIZED_WIRE_8;
wire	[7:0] SYNTHESIZED_WIRE_165;
wire	[7:0] SYNTHESIZED_WIRE_12;
wire	[7:0] SYNTHESIZED_WIRE_13;
wire	[7:0] SYNTHESIZED_WIRE_14;
wire	[7:0] SYNTHESIZED_WIRE_166;
wire	[7:0] SYNTHESIZED_WIRE_167;
wire	[7:0] SYNTHESIZED_WIRE_168;
wire	[7:0] SYNTHESIZED_WIRE_18;
wire	[7:0] SYNTHESIZED_WIRE_19;
wire	[7:0] SYNTHESIZED_WIRE_20;
wire	[7:0] SYNTHESIZED_WIRE_169;
wire	[7:0] SYNTHESIZED_WIRE_24;
wire	[7:0] SYNTHESIZED_WIRE_25;
wire	[7:0] SYNTHESIZED_WIRE_26;
wire	[7:0] SYNTHESIZED_WIRE_27;
wire	[7:0] SYNTHESIZED_WIRE_170;
wire	[7:0] SYNTHESIZED_WIRE_29;
wire	[7:0] SYNTHESIZED_WIRE_171;
wire	[7:0] SYNTHESIZED_WIRE_172;
wire	[7:0] SYNTHESIZED_WIRE_173;
wire	[7:0] SYNTHESIZED_WIRE_33;
wire	[7:0] SYNTHESIZED_WIRE_35;
wire	[7:0] SYNTHESIZED_WIRE_174;
wire	[7:0] SYNTHESIZED_WIRE_175;
wire	SYNTHESIZED_WIRE_176;
wire	SYNTHESIZED_WIRE_177;
wire	[7:0] SYNTHESIZED_WIRE_178;
wire	[2:0] SYNTHESIZED_WIRE_51;
wire	[7:0] SYNTHESIZED_WIRE_179;
wire	[7:0] SYNTHESIZED_WIRE_180;
wire	[7:0] SYNTHESIZED_WIRE_181;
wire	[7:0] SYNTHESIZED_WIRE_182;
wire	[7:0] SYNTHESIZED_WIRE_183;
wire	[7:0] SYNTHESIZED_WIRE_69;
wire	[7:0] SYNTHESIZED_WIRE_71;
wire	[7:0] SYNTHESIZED_WIRE_72;
wire	[7:0] SYNTHESIZED_WIRE_74;
wire	[7:0] SYNTHESIZED_WIRE_75;
wire	[7:0] SYNTHESIZED_WIRE_76;
wire	[7:0] SYNTHESIZED_WIRE_77;
wire	[7:0] SYNTHESIZED_WIRE_78;
wire	[7:0] SYNTHESIZED_WIRE_79;
wire	[7:0] SYNTHESIZED_WIRE_80;
wire	[7:0] SYNTHESIZED_WIRE_81;
wire	[7:0] SYNTHESIZED_WIRE_82;
wire	[7:0] SYNTHESIZED_WIRE_84;
wire	[7:0] SYNTHESIZED_WIRE_184;
wire	[7:0] SYNTHESIZED_WIRE_87;
wire	[7:0] SYNTHESIZED_WIRE_88;
wire	[7:0] SYNTHESIZED_WIRE_89;
wire	[7:0] SYNTHESIZED_WIRE_90;
wire	[7:0] SYNTHESIZED_WIRE_91;
wire	[7:0] SYNTHESIZED_WIRE_185;
wire	[7:0] SYNTHESIZED_WIRE_93;
wire	[7:0] SYNTHESIZED_WIRE_94;
wire	[7:0] SYNTHESIZED_WIRE_95;
wire	[7:0] SYNTHESIZED_WIRE_97;
wire	[7:0] SYNTHESIZED_WIRE_98;
wire	[7:0] SYNTHESIZED_WIRE_186;
wire	[7:0] SYNTHESIZED_WIRE_100;
wire	[7:0] SYNTHESIZED_WIRE_101;
wire	[7:0] SYNTHESIZED_WIRE_102;
wire	[7:0] SYNTHESIZED_WIRE_103;
wire	[7:0] SYNTHESIZED_WIRE_104;
wire	[7:0] SYNTHESIZED_WIRE_105;
wire	[7:0] SYNTHESIZED_WIRE_106;
wire	[7:0] SYNTHESIZED_WIRE_108;
wire	[7:0] SYNTHESIZED_WIRE_109;
wire	[7:0] SYNTHESIZED_WIRE_110;
wire	[7:0] SYNTHESIZED_WIRE_111;
wire	[7:0] SYNTHESIZED_WIRE_112;
wire	[7:0] SYNTHESIZED_WIRE_113;
wire	[7:0] SYNTHESIZED_WIRE_114;
wire	[7:0] SYNTHESIZED_WIRE_115;
wire	[7:0] SYNTHESIZED_WIRE_116;
wire	[7:0] SYNTHESIZED_WIRE_117;
wire	[7:0] SYNTHESIZED_WIRE_119;
wire	[7:0] SYNTHESIZED_WIRE_120;
wire	[7:0] SYNTHESIZED_WIRE_121;
wire	[7:0] SYNTHESIZED_WIRE_187;
wire	[7:0] SYNTHESIZED_WIRE_188;
wire	[7:0] SYNTHESIZED_WIRE_189;
wire	[7:0] SYNTHESIZED_WIRE_190;
wire	[7:0] SYNTHESIZED_WIRE_191;
wire	[7:0] SYNTHESIZED_WIRE_192;
wire	[7:0] SYNTHESIZED_WIRE_193;
wire	[7:0] SYNTHESIZED_WIRE_194;
wire	[7:0] SYNTHESIZED_WIRE_138;
wire	[7:0] SYNTHESIZED_WIRE_139;
wire	[7:0] SYNTHESIZED_WIRE_140;
wire	[7:0] SYNTHESIZED_WIRE_141;
wire	[7:0] SYNTHESIZED_WIRE_142;
wire	[7:0] SYNTHESIZED_WIRE_143;
wire	[7:0] SYNTHESIZED_WIRE_144;
wire	[7:0] SYNTHESIZED_WIRE_145;
wire	[7:0] SYNTHESIZED_WIRE_152;
wire	[7:0] SYNTHESIZED_WIRE_195;
wire	[7:0] SYNTHESIZED_WIRE_154;
wire	[7:0] SYNTHESIZED_WIRE_196;
wire	[7:0] SYNTHESIZED_WIRE_156;
wire	[7:0] SYNTHESIZED_WIRE_157;
wire	[7:0] SYNTHESIZED_WIRE_160;





lpm_dff4	b2v_inst(
	.clock(clk),
	.data(inp),
	.q(SYNTHESIZED_WIRE_161));


lpm_dff4	b2v_inst1(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_161),
	.q(SYNTHESIZED_WIRE_178));


lpm_add_sub4	b2v_inst10(
	.dataa(SYNTHESIZED_WIRE_162),
	.datab(SYNTHESIZED_WIRE_163),
	.result(SYNTHESIZED_WIRE_72));


shifon	b2v_inst100(
	.A(SYNTHESIZED_WIRE_164),
	.Y(SYNTHESIZED_WIRE_4));


lpm_add_sub5	b2v_inst101(
	.dataa(SYNTHESIZED_WIRE_4),
	.datab(SYNTHESIZED_WIRE_5),
	.result(SYNTHESIZED_WIRE_6));


lpm_dff6	b2v_inst102(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_6),
	.q(SYNTHESIZED_WIRE_165));


lpm_add_sub5	b2v_inst103(
	.dataa(SYNTHESIZED_WIRE_7),
	.datab(SYNTHESIZED_WIRE_8),
	.result(SYNTHESIZED_WIRE_12));


lpm_dff6	b2v_inst104(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_164),
	.q(SYNTHESIZED_WIRE_7));


shifon	b2v_inst105(
	.A(SYNTHESIZED_WIRE_165),
	.Y(SYNTHESIZED_WIRE_8));


lpm_dff6	b2v_inst106(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_165),
	.q(outp3));


lpm_dff6	b2v_inst107(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_12),
	.q(outp5));


lpm_add_sub5	b2v_inst108(
	.dataa(SYNTHESIZED_WIRE_13),
	.datab(SYNTHESIZED_WIRE_14),
	.result(SYNTHESIZED_WIRE_18));


shif	b2v_inst109(
	.A(SYNTHESIZED_WIRE_166),
	.Y(SYNTHESIZED_WIRE_14));


lpm_add_sub4	b2v_inst11(
	.dataa(SYNTHESIZED_WIRE_167),
	.datab(SYNTHESIZED_WIRE_168),
	.result(SYNTHESIZED_WIRE_74));


lpm_dff6	b2v_inst110(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_18),
	.q(SYNTHESIZED_WIRE_169));


lpm_add_sub5	b2v_inst111(
	.dataa(SYNTHESIZED_WIRE_19),
	.datab(SYNTHESIZED_WIRE_20),
	.result(SYNTHESIZED_WIRE_24));


shif	b2v_inst112(
	.A(SYNTHESIZED_WIRE_169),
	.Y(SYNTHESIZED_WIRE_19));


lpm_dff6	b2v_inst113(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_166),
	.q(SYNTHESIZED_WIRE_20));


lpm_dff6	b2v_inst114(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_169),
	.q(outp6));


lpm_dff6	b2v_inst115(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_24),
	.q(outp2));


lpm_add_sub4	b2v_inst116(
	.dataa(SYNTHESIZED_WIRE_25),
	.datab(SYNTHESIZED_WIRE_26),
	.result(SYNTHESIZED_WIRE_27));


lpm_dff6	b2v_inst117(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_27),
	.q(SYNTHESIZED_WIRE_170));


lpm_dff6	b2v_inst118(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_170),
	.q(outp7));


shifon	b2v_inst119(
	.A(SYNTHESIZED_WIRE_29),
	.Y(SYNTHESIZED_WIRE_33));


lpm_add_sub4	b2v_inst12(
	.dataa(SYNTHESIZED_WIRE_171),
	.datab(SYNTHESIZED_WIRE_172),
	.result(SYNTHESIZED_WIRE_75));


lpm_dff6	b2v_inst120(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_173),
	.q(SYNTHESIZED_WIRE_29));


lpm_add_sub5	b2v_inst121(
	.dataa(SYNTHESIZED_WIRE_33),
	.datab(SYNTHESIZED_WIRE_170),
	.result(SYNTHESIZED_WIRE_35));


lpm_dff6	b2v_inst122(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_35),
	.q(outp1));


lpm_add_sub5	b2v_inst13(
	.dataa(SYNTHESIZED_WIRE_171),
	.datab(SYNTHESIZED_WIRE_172),
	.result(SYNTHESIZED_WIRE_76));


lpm_add_sub5	b2v_inst14(
	.dataa(SYNTHESIZED_WIRE_167),
	.datab(SYNTHESIZED_WIRE_168),
	.result(SYNTHESIZED_WIRE_77));


lpm_add_sub5	b2v_inst15(
	.dataa(SYNTHESIZED_WIRE_162),
	.datab(SYNTHESIZED_WIRE_163),
	.result(SYNTHESIZED_WIRE_78));


lpm_add_sub5	b2v_inst16(
	.dataa(SYNTHESIZED_WIRE_174),
	.datab(SYNTHESIZED_WIRE_175),
	.result(SYNTHESIZED_WIRE_79));

assign	SYNTHESIZED_WIRE_176 = q_ALTERA_SYNTHESIZED0[0] & q_ALTERA_SYNTHESIZED0[1] & q_ALTERA_SYNTHESIZED0[2];


lpm_latch0	b2v_inst18(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_161),
	.q(SYNTHESIZED_WIRE_175));


lpm_latch0	b2v_inst19(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_178),
	.q(SYNTHESIZED_WIRE_163));


lpm_dff4	b2v_inst2(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_178),
	.q(SYNTHESIZED_WIRE_179));


lpm_dff5	b2v_inst20(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_51),
	.q(q_ALTERA_SYNTHESIZED0));


lpm_latch0	b2v_inst21(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_179),
	.q(SYNTHESIZED_WIRE_168));


lpm_latch0	b2v_inst22(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_180),
	.q(SYNTHESIZED_WIRE_172));


lpm_latch0	b2v_inst23(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_181),
	.q(SYNTHESIZED_WIRE_171));


lpm_latch0	b2v_inst24(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_182),
	.q(SYNTHESIZED_WIRE_167));


lpm_latch0	b2v_inst25(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_183),
	.q(SYNTHESIZED_WIRE_162));


lpm_latch0	b2v_inst26(
	.gate(SYNTHESIZED_WIRE_176),
	.aclr(SYNTHESIZED_WIRE_177),
	.data(SYNTHESIZED_WIRE_69),
	.q(SYNTHESIZED_WIRE_174));

assign	SYNTHESIZED_WIRE_177 =  ~SYNTHESIZED_WIRE_176;


lpm_dff6	b2v_inst28(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_71),
	.q(SYNTHESIZED_WIRE_117));


lpm_dff6	b2v_inst29(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_72),
	.q(SYNTHESIZED_WIRE_114));


lpm_dff4	b2v_inst3(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_179),
	.q(SYNTHESIZED_WIRE_180));


lpm_dff6	b2v_inst30(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_74),
	.q(SYNTHESIZED_WIRE_111));


lpm_dff6	b2v_inst31(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_75),
	.q(SYNTHESIZED_WIRE_106));


lpm_dff6	b2v_inst32(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_76),
	.q(SYNTHESIZED_WIRE_103));


lpm_dff6	b2v_inst33(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_77),
	.q(SYNTHESIZED_WIRE_80));


lpm_dff6	b2v_inst34(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_78),
	.q(SYNTHESIZED_WIRE_184));


lpm_dff6	b2v_inst35(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_79),
	.q(SYNTHESIZED_WIRE_84));


lpm_add_sub5	b2v_inst36(
	.dataa(SYNTHESIZED_WIRE_80),
	.datab(SYNTHESIZED_WIRE_81),
	.result(SYNTHESIZED_WIRE_82));


lpm_dff6	b2v_inst37(
	.clock(clk),
	
	.data(SYNTHESIZED_WIRE_82),
	.q(SYNTHESIZED_WIRE_185));


shif1	b2v_inst38(
	.A(SYNTHESIZED_WIRE_173),
	.Y(SYNTHESIZED_WIRE_26));


lpm_dff6	b2v_inst39(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_84),
	.q(SYNTHESIZED_WIRE_95));


lpm_dff4	b2v_inst4(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_180),
	.q(SYNTHESIZED_WIRE_181));


lpm_add_sub4	b2v_inst41(
	.dataa(SYNTHESIZED_WIRE_184),
	.datab(SYNTHESIZED_WIRE_87),
	.result(SYNTHESIZED_WIRE_88));


lpm_dff6	b2v_inst42(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_88),
	.q(SYNTHESIZED_WIRE_90));


lpm_add_sub4	b2v_inst44(
	.dataa(SYNTHESIZED_WIRE_89),
	.datab(SYNTHESIZED_WIRE_90),
	.result(SYNTHESIZED_WIRE_91));


lpm_dff6	b2v_inst45(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_91),
	.q(SYNTHESIZED_WIRE_186));


lpm_add_sub5	b2v_inst47(
	.dataa(SYNTHESIZED_WIRE_185),
	.datab(SYNTHESIZED_WIRE_93),
	.result(SYNTHESIZED_WIRE_94));


lpm_dff6	b2v_inst48(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_94),
	.q(SYNTHESIZED_WIRE_192));


lpm_dff6	b2v_inst49(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_95),
	.q(SYNTHESIZED_WIRE_97));


lpm_dff4	b2v_inst5(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_181),
	.q(SYNTHESIZED_WIRE_182));


lpm_dff6	b2v_inst50(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_97),
	.q(SYNTHESIZED_WIRE_98));


lpm_dff6	b2v_inst51(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_98),
	.q(SYNTHESIZED_WIRE_194));


lpm_dff6	b2v_inst52(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_186),
	.q(SYNTHESIZED_WIRE_193));


lpm_dff6	b2v_inst53(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_100),
	.q(SYNTHESIZED_WIRE_191));


lpm_dff6	b2v_inst54(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_101),
	.q(SYNTHESIZED_WIRE_100));


lpm_dff6	b2v_inst55(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_102),
	.q(SYNTHESIZED_WIRE_101));


lpm_dff6	b2v_inst56(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_103),
	.q(SYNTHESIZED_WIRE_102));


lpm_dff6	b2v_inst57(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_104),
	.q(SYNTHESIZED_WIRE_108));


lpm_dff6	b2v_inst58(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_105),
	.q(SYNTHESIZED_WIRE_104));


lpm_dff6	b2v_inst59(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_106),
	.q(SYNTHESIZED_WIRE_105));


lpm_dff4	b2v_inst6(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_182),
	.q(SYNTHESIZED_WIRE_183));


lpm_dff6	b2v_inst60(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_108),
	.q(SYNTHESIZED_WIRE_188));


lpm_dff6	b2v_inst61(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_109),
	.q(SYNTHESIZED_WIRE_119));


lpm_dff6	b2v_inst62(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_110),
	.q(SYNTHESIZED_WIRE_109));


lpm_dff6	b2v_inst63(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_111),
	.q(SYNTHESIZED_WIRE_110));


lpm_dff6	b2v_inst64(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_112),
	.q(SYNTHESIZED_WIRE_121));


lpm_dff6	b2v_inst65(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_113),
	.q(SYNTHESIZED_WIRE_112));


lpm_dff6	b2v_inst66(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_114),
	.q(SYNTHESIZED_WIRE_113));


lpm_dff6	b2v_inst67(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_115),
	.q(SYNTHESIZED_WIRE_120));


lpm_dff6	b2v_inst68(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_116),
	.q(SYNTHESIZED_WIRE_115));


lpm_dff6	b2v_inst69(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_117),
	.q(SYNTHESIZED_WIRE_116));


lpm_dff4	b2v_inst7(
	.clock(clk),
	.data(SYNTHESIZED_WIRE_183),
	.q(SYNTHESIZED_WIRE_69));


lpm_dff6	b2v_inst70(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_119),
	.q(SYNTHESIZED_WIRE_190));


lpm_dff6	b2v_inst71(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_120),
	.q(SYNTHESIZED_WIRE_187));


lpm_dff6	b2v_inst72(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_121),
	.q(SYNTHESIZED_WIRE_189));


lpm_add_sub4	b2v_inst73(
	.dataa(SYNTHESIZED_WIRE_187),
	.datab(SYNTHESIZED_WIRE_188),
	.result(SYNTHESIZED_WIRE_144));


lpm_add_sub4	b2v_inst74(
	.dataa(SYNTHESIZED_WIRE_189),
	.datab(SYNTHESIZED_WIRE_190),
	.result(SYNTHESIZED_WIRE_145));


lpm_add_sub4	b2v_inst75(
	.dataa(SYNTHESIZED_WIRE_191),
	.datab(SYNTHESIZED_WIRE_192),
	.result(SYNTHESIZED_WIRE_143));


lpm_add_sub4	b2v_inst76(
	.dataa(SYNTHESIZED_WIRE_193),
	.datab(SYNTHESIZED_WIRE_194),
	.result(SYNTHESIZED_WIRE_142));


lpm_add_sub5	b2v_inst77(
	.dataa(SYNTHESIZED_WIRE_193),
	.datab(SYNTHESIZED_WIRE_194),
	.result(SYNTHESIZED_WIRE_141));


lpm_add_sub5	b2v_inst78(
	.dataa(SYNTHESIZED_WIRE_191),
	.datab(SYNTHESIZED_WIRE_192),
	.result(SYNTHESIZED_WIRE_138));


lpm_add_sub5	b2v_inst79(
	.dataa(SYNTHESIZED_WIRE_189),
	.datab(SYNTHESIZED_WIRE_190),
	.result(SYNTHESIZED_WIRE_140));


lpm_counter0	b2v_inst8(
	.clock(clk),
	.q(SYNTHESIZED_WIRE_51));


lpm_add_sub5	b2v_inst80(
	.dataa(SYNTHESIZED_WIRE_187),
	.datab(SYNTHESIZED_WIRE_188),
	.result(SYNTHESIZED_WIRE_139));


lpm_dff6	b2v_inst81(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_138),
	.q(SYNTHESIZED_WIRE_25));


lpm_dff6	b2v_inst82(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_139),
	.q(SYNTHESIZED_WIRE_164));


lpm_dff6	b2v_inst83(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_140),
	.q(SYNTHESIZED_WIRE_5));


lpm_dff6	b2v_inst84(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_141),
	.q(SYNTHESIZED_WIRE_173));


lpm_dff6	b2v_inst85(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_142),
	.q(SYNTHESIZED_WIRE_166));


lpm_dff6	b2v_inst86(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_143),
	.q(SYNTHESIZED_WIRE_13));


lpm_dff6	b2v_inst87(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_144),
	.q(SYNTHESIZED_WIRE_152));


lpm_dff6	b2v_inst88(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_145),
	.q(SYNTHESIZED_WIRE_195));


shif	b2v_inst89(
	.A(SYNTHESIZED_WIRE_185),
	.Y(SYNTHESIZED_WIRE_89));


lpm_add_sub4	b2v_inst9(
	.dataa(SYNTHESIZED_WIRE_174),
	.datab(SYNTHESIZED_WIRE_175),
	.result(SYNTHESIZED_WIRE_71));


shifon	b2v_inst90(
	.A(SYNTHESIZED_WIRE_184),
	.Y(SYNTHESIZED_WIRE_81));


shifon	b2v_inst91(
	.A(SYNTHESIZED_WIRE_186),
	.Y(SYNTHESIZED_WIRE_93));


shifon	b2v_inst92(
	.A(SYNTHESIZED_WIRE_185),
	.Y(SYNTHESIZED_WIRE_87));


lpm_add_sub4	b2v_inst93(
	.dataa(SYNTHESIZED_WIRE_152),
	.datab(SYNTHESIZED_WIRE_195),
	.result(SYNTHESIZED_WIRE_154));


lpm_dff6	b2v_inst94(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_154),
	.q(SYNTHESIZED_WIRE_196));


shifon	b2v_inst95(
	.A(SYNTHESIZED_WIRE_196),
	.Y(SYNTHESIZED_WIRE_156));


lpm_add_sub5	b2v_inst96(
	.dataa(SYNTHESIZED_WIRE_156),
	.datab(SYNTHESIZED_WIRE_157),
	.result(SYNTHESIZED_WIRE_160));


lpm_dff6	b2v_inst97(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_196),
	.q(outp0));


lpm_dff6	b2v_inst98(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_195),
	.q(SYNTHESIZED_WIRE_157));


lpm_dff6	b2v_inst99(
	.clock(clk),
	.aclr(cle),
	.data(SYNTHESIZED_WIRE_160),
	.q(outp4));

assign	q0 = q_ALTERA_SYNTHESIZED0;

endmodule
 watermarking-architecture
